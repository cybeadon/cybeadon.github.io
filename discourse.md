---
title: Discourse
layout: page
---

Test page for embedding discourse.

<div id='discourse-comments'></div>

<script> 
    DiscourseEmbed = { discourseUrl: 'https://blog.oecloud.io/', discourseEmbedUrl: 'https://cybeadon.com/discourse/' }; 
    (function(){
        var d = document.createElement('script'); 
        d.type = 'text/javascript'; d.async = true; d.src = DiscourseEmbed.discourseUrl + 'javascripts/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(d); 
    })();
</script>