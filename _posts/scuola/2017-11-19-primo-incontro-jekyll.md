---
layout: page
sidebar: right
subheadline: Jekyll
title:  "Prova del static site generator"
teaser: "Back to the future!"
breadcrumb: true
categories:
    - scuola
image:
    title: jekyll.png
    thumb: jekyll-thumb.png
    caption: Jekyll
    caption_url: http://www.jekyll.com/
header:
    image_fullwidth: "kids-coding.png"
    title: Learn
comments: true
show_meta: true
tags:
    - scuola
---
- Url sito: {% raw %}{% {{ site.url }} %}{% endraw %} = {{ site.url }}
- Url delle immagini del sito: {% raw %}{% {{ site.urlimg }} %}{% endraw %} = {{ site.urlimg }}
- Relative Url: {% raw %}{% {{ "/assets/style.css" | relative_url }} %}{% endraw %} = {{ "/assets/style.css" | relative_url }}
- Absolute Url: {% raw %}{% {{ "/assets/style.css" | absolute_url }} %}{% endraw %} = {{ "/assets/style.css" | absolute_url }}
- Excerpt: {% raw %}{% {{ page.excerpt }} %}{% endraw %} = {{ page.excerpt }}
