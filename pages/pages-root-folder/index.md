---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:

widget1:
  title: "Organization Blueprints"
  url: '/blueprints/'
  image: 320px-Blueprint_of_Victory_-_NARA_-_534555.jpg
  text: 'Document templates to use as you start your lab or update procedures.'
widget2:
  title: "LeafSpring Blog"
  url: 'http://leafspring.labcarpentry.org'
  image: header-bus.jpg
  text: 'A Dear Abby style blog for scientists with questions on running a lab.'
widget3:
  title: "Workshops & Training"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: ''
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
#  url: /blueprints/
#  text: Check out our new lab manual templates ›
#  style: alert
#permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
