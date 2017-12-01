---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
  caption: Comic Arts by Marianna Balducci
  caption_url: "http://mariannabalducci.it//"
widget1:
  title: "Notizie & Articoli"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: 'Condividiamo sul blog il pensiero dei nostri mentor, campioni, ninja ed ovviamente del nostro venerando  <a href="http://www.mind-spa.it/"><em>Sensei</em></a>.
  Pubblichiamo qui anche le informazioni sulle novità del mondo Coderdojo.
  I post si possono cammentare. Happy blogging!'
widget2:
  title: "Cos'è il CoderDojo?"
  url: '/chi-siamo/'
  text: '<em>CoderDojo Rimini</em> è:<br/>
  1. Coding<br/>
  2. Scratch<br/>
  3. Robotica con <a href="https://www.arduino.cc/">Arduino</a> e <a href="https://www.raspberrypi.org/">Raspberry</a>.<br/>
  4. Web development con Jekyll.<br/>
  5. Divertimento!'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/coderdojorimini/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Scarica Scratch"
  url: '/risorse/'
  image: widget-github-303x182.jpg
  text: '<em>Scratch</em> è gratis, funziona su Windows, Mac e Linux. Scaricalo e comincia a sviluppare. Prendi la versione più recente <a href="https://scratch.mit.edu/download">Scratch 2.0</a> oppure quella più stabile <a href="http://scratch.mit.edu/scratch_1.4/">Scratch 1.4</a>. Puoi anche divertirti <a href="https://scratch.mit.edu/projects/editor/?tip_bar=home">online</a>! Scrivici via Twitter <a href="http://twitter.com/coderdojoRN">@coderdojoRN</a>.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /newsletter/
  text: Tienimi informato sui prossimi incontri ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/70kwN4cgBjM" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
