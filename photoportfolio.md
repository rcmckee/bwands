---
layout: page
title: photoportfolio
permalink: /photoportfolio/
---


{% for image in site.static_files %}
<!--
    {% if image.path contains 'photoportfolio' %}

-->
<div class="project">
    <div class= "thumbnail">
        <a href="{{ site.baseurl }}{{ image.path }}">
            <img class="thumbnail" src="/img/blank.png" alt="" data-echo="{{ site.baseurl }}{{ image.path }}" height=600  width=800 >
        </a>
    </div>
</div>

<!--
    {% endif %}
-->
{% endfor %}




<!-- this is for the lightbox --> 
<script type="text/javascript" src="/js/lightbox.js"></script>
<link rel="stylesheet" href="/css/lightbox.css">