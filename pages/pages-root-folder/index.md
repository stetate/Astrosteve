---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: astrophotos/20x10lEnh.jpg
widget1:
  title: "Image Posts"
  url: 'http://stetate.github.io/Astrosteve/blog/'
  image: astronomy203.png
  text: 'Lastest Images / News and activities'
widget2:
  title: "How To...."
  url: /getting-started/
  image: astronomy203.png
  text: 'The long road is one that never ends -- there is always something new to work on and learn'
widget3:
  title: "Equipment"
  url: /equipment/
  image: astronomy203.png
  text: 'Coming soon a full list and compiled version of images taken'

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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

