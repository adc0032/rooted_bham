---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header01_cityscape.jpeg
widget1:
  title: "Explore Our Roots"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: alby_hendrick_bhamautumn.jpeg
  text: 'A city is nothing without people. <em>Rooted In Birmingham</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'
widget2:
  title: "About Our Roots"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href="http://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://adc0032.github.io/rooted_bham/images/morrisave_jamie.jpeg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Strengthen Our Roots"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: JasonParks_courtney.jpeg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
  url: https://tinyletter.com/adc0032
  text: Keep me informed on Rooted In Birmingham ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/e95Vk5eW7ys" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>