---
layout: page
title: about
permalink: /about/
galleries:
  - title: Link to homepage
    image: /img/photoportfolio/16109952671276.png
    url: https:www.gizmodo.com
  - title: Link to image gallery
    image: /img/photoportfolio/16109952671277.png
    url: https://www.techcrunch.com
---

{% if page.galleries %}

{% include image-gallery-index.html %}

{% endif %}