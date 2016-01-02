---
layout: home
permalink: /
image:
  feature: home.jpg
---
<div>
<h2 class="post-title"><i class="fa fa-exclamation-triangle"></i> Work in Progress!</h2>
  <p>Il blog è ancora in fase di migrazione / assemblamento! Non dovresti essere qui!</p></div>

<div class="tiles">
<h2 class="post-title"><i class="fa fa-clock-o"></i> Post Freschi</h2>
  <p>{% for post in site.posts limit:4 %}
  {% include post-grid.html %}
  {% endfor %}
  </p></div>

<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="La ricerca porta alla verità. (disse Socrate. Poi però è morto)">
<ul id="results-container"></ul>
</div>

<!-- Script pointing to jekyll-search.js -->
<script src="{{ site.baseurl }}/bower_components/simple-jekyll-search/dest/jekyll-search.js" type="text/javascript"></script>

<script type="text/javascript">
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json',
})
</script>

<div class="tiles">

<div class="tile">
  <h2 class="post-title"> <i class="fa fa-home"></i> Dove ti trovi</h2>
  <p class="post-excerpt">Xaba Cadabra è un blog, un Cetramod ad personam ed un aggregatore di tutto quello che <a href="/about/">Xab</a> combina in rete (o quasi). Per saperne di più sulla sua storia, <a href="/blog/story/">clicca qui.</a></p> 
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-clock-o"></i> Ultimi Post</h2>
  <p>
  <ul class="posts">  
  {% for post in site.posts limit:3 %}  
     <li>  
       <span>{{ post.date | date_to_string }}</span> &raquo;  
       <a href="{{ BASE_PATH }}{{ post.url }}">  
       {{ post.title }}</a>  
     </li>  
  {% endfor %}  
 </ul>
 </p>
 <p>
  {% for post in site.posts limit:1 %}
  {% include post-grid.html %}
  {% endfor %}
 </p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-phone-square"></i> Contatti</h2>
  <p class="post-excerpt">Allo stato attuale il modo migliore per avere mie notizie all'infuori di questo blog è <a href="https://twitter.com/Xabaras89"><b>inviarmi un tweet</b></a> (e preciso TWEET: i messaggi privati non li leggo dal 2010). Per il resto, date pure un'occhiata ai profili sociali qui sotto.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-creative-commons"></i> Licenza</h2>
  <p class="post-excerpt"><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licenza Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" align="center"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Xaba Cadabra</span> di<a xmlns:cc="http://creativecommons.org/ns#" href="http://xabacadabra.github.io/" property="cc:attributionName" rel="cc:attributionURL"> Andrea Corinti</a> è distribuito con Licenza <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale</a>.</p>
</div><!-- /.tile -->

</div><!-- /.tiles -->
