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
    title: jekyll.jpg
    thumb: jekyll-thumb.jpg
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

RELATIVE URL
{{ "/assets/style.css" | relative_url }}
ABSOLUTE URL
{{ "/assets/style.css" | absolute_url }}
DATA
{{ site.time | date_to_rfc822 }}
{{ site.time | date_to_long_string }}

{{ page.excerpt | markdownify }}

{{ "a \n b" | normalize_whitespace }}

{{ page.tags | sort }}
{{ site.posts | sort: 'author' }}
{{ site.pages | sort: 'title', 'last' }}
{{ site.pages | sample }}
{{ site.pages | sample:2 }}

LINK
[Link to a post]({{ site.baseurl }})

PATH
{{ page.path }}

PERMALINK
{{ site.baseurl }}{% post_url 2017-11-20-luoghi-del-coderdojo %}

{{ site.urlimg }}
{{ site.url }}
