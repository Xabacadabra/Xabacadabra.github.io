---
layout: home
permalink: /
image:
  feature: centra.gif
---

<div><h2 class="post-title"><i class="fa fa-clock-o"></i> Ultimi Post</h2></div>

<div class="tiles">
  {% for post in site.posts limit:4 %}
    {% include post-grid.html %}
  {% endfor %}
</div>

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

<div>
  <figure>
   <p style="text-align:center;"><img src="/images/SCIMMIE.gif" alt="scimmie"></p>
</figure>
</div>

<div class="tiles">

<div class="tile">
  <h2 class="post-title"> <i class="fa fa-home"></i> Dove ti trovi</h2>
  <p class="post-excerpt">Xaba Cadabra è un blog, un <i><a href="/2013/cetramod/">Cetramod</a> ad personam</i> ed un aggregatore di tutto quello che <a href="/about/"><b>Xab</b></a> combina in rete (o quasi).</p> 

  <p>Per saperne di più sulla sua storia, <a href="/blog/story/"><b>clicca qui.</b></a></p> 
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-rocket"></i> Powered By</h2>
  <p><a href="http://jekyllrb.com/">Jekyll</a>, <a href="https://github.com/">Github</a>, <a href="http://mmistakes.github.io/skinny-bones-jekyll/">Skinny Bones</a> e <a href="https://disqus.com/">Disqus</a>.</p>
  <p>Xaba Cadabra <b>è al 100% privo di pubblicità e <a href="https://it.wikipedia.org/wiki/Cookie">cookies</a></b></p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-phone-square"></i> Contatti</h2>
  <p class="post-excerpt">Allo stato attuale il modo migliore per avere mie notizie all'infuori di questo blog è <a href="https://twitter.com/Xabaras89"><b>inviarmi un tweet</b></a>. (no messaggi privati please)</p>
  <p>Per il resto, valgono i profili sociali qua sotto</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-creative-commons"></i> Licenza</h2>
  <p class="post-excerpt"><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licenza Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" align="center"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Xaba Cadabra</span> di<a xmlns:cc="http://creativecommons.org/ns#" href="http://xabacadabra.github.io/" property="cc:attributionName" rel="cc:attributionURL"> Andrea Corinti</a> è distribuito con Licenza <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale</a>.</p>
</div><!-- /.tile -->

</div><!-- /.tiles -->
