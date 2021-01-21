---
layout: page
title: about
permalink: /about/
galleries:
  - title: Link to homepage
    image: /img/1.jpg
    url: https:www.gizmodo.com
  - title: Link to image gallery
    image: /img/2.jpg
    url: https://www.techcrunch.com
---

{% if page.galleries %}

{% include image-gallery-index.html %}

{% endif %}