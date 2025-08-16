---
layout: post-single
title: Latest Article
permalink: /latest
---
<div class="section-title">
    <h2><span>Latest Article</span></h2>
</div>

<!-- Begin Article
================================================== -->
{% assign post = site.posts | first %}
{% include post-single.html %}

<!-- Begin Comments
================================================== -->
{% if post.comments != false %}
<div class="container">
<div id="comments" class="row justify-content-center mb-5">
<div class="col-md-8">
<section class="disqus">
    <div id="disqus_thread"></div>
    <script type="text/javascript">
        var disqus_shortname = '{{site.disqus}}'; 
        var disqus_developer = 0;
        var disqus_config = function () {
            this.page.url = 'https://localhost:4000{{post.url}}';
         };
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = window.location.protocol + '//' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
    <a href="http://disqus.com" class="dsq-brlink">comments powered by <span class="logo-disqus">Disqus</span></a>
</section>
</div>
</div>
</div>
{% endif %}
<!--End Comments
================================================== -->