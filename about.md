---
layout: page
title: about
permalink: /about/
galleries:
  - title: Link to homepage
    image: /bwands/img/1.jpg
    url: https:www.gizmodo.com
  - title: Link to image gallery
    image: /bwands/img/2.jpg
    url: https://www.techcrunch.com
---

{% if page.galleries %}

{% include image-gallery-index.html %}

{% endif %}