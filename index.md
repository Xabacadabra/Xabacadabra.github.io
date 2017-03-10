---
layout: home
permalink: /
image:
  feature: gardenight.gif
---

<div><h2 class="post-title"><i class="fa fa-search"></i> Cerca su Xaba Cadabra</h2></div>

<!--ricercagoogle-->
<script>
  (function() {
    var cx = '000160596931109432273:x8yvqtu5jqy';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = 'https://cse.google.com/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:search></gcse:search>
<!--/ricercagoogle-->

<div><h2 class="post-title"><i class="fa fa-clock-o"></i> Ultimi Post</h2></div>

<div class="tiles">
  {% for post in site.posts limit:8 %}
    {% include post-grid.html %}
  {% endfor %}
  
</div>

<div class="tiles">

<div class="tile">
  <h2 class="post-title"> <i class="fa fa-home"></i> Dove ti trovi</h2>
  <p class="post-excerpt">Xaba Cadabra è una <i>Blog Webzine</i> nonché epicentro di tutto quello che <a href="http://xabacadabra.com/andrea-corinti/"><b>Xab</b></a> combina in rete.</p> 

  <p>Per saperne di più sulla sua storia, <a href="/blog/story/"><b>clicca qui.</b></a></p> 
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-rocket"></i> Powered By</h2>
  <p class="post-excerpt">Questo sito è costruito utilizzando <a href="http://jekyllrb.com/">Jekyll</a>, <a href="https://github.com/">Github</a>, <a href="http://mmistakes.github.io/skinny-bones-jekyll/">Skinny Bones</a> e <a href="https://disqus.com/">Disqus</a>.</p>
  <p class="post-excerpt">Xaba Cadabra <b>è al 100% privo di <a href="https://it.wikipedia.org/wiki/Cookie">cookies</a></b></p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-phone-square"></i> Contatti</h2>
  <p class="post-excerpt"> Potete mandarmi una <a href="mailto:xabarasff@gmail.com"><b>mail</b></a> oppure <a href="https://twitter.com/Xabaras89" rel="me"><b>scrivermi un tweet</b></a> (ma evitate messaggi privati, non li leggo!).</p>
  <p class="post-excerpt">Per il resto, valgono i profili sociali qua sotto</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title"><i class="fa fa-creative-commons"></i> Licenza</h2>
  <p class="post-excerpt">Xaba Cadabra di Andrea Corinti è protetto da:</p> 
  <p class="post-excerpt">Licenza <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale</a>.</p>
</div><!-- /.tile -->

</div><!-- /.tiles -->
