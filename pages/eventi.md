---
layout: page
show_meta: false
title: "Eventi"
subheadline: "Calendario degli incontri programmati"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/eventi/"
---

<iframe src="https://calendar.google.com/calendar/embed?src=coderdojorimini%40gmail.com&ctz=Europe/Rome" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

Eventi pubblicati su [Zen CoderDojo](https://zen.coderdojo.com/dojos/it/rimini-province-of-rimini/rimini "Evento CoderDojoRimini")



<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
