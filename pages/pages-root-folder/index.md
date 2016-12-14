---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:

widget1:
  title: "Blueprints"
  url: '/blueprints/'
  image: 320px-Blueprint_of_Victory_-_NARA_-_534555.jpg
  text: 'Document templates for starting your lab and writing grants.'
widget2:
  title: "LeafSpring Blog"
  url: 'http://labcarpentry.org/leafspring'
  image: Tree_fern_frond_at_Akatarawa_small.jpg
  text: 'A Dear Abby style blog for scientists running research labs.'
widget3:
  title: "Workshops"
  url: '/workshops/'
  image: Fail-a-lot-publicly.png
  text: 'Schedule Lab Carpentry discussion and training at your institution.'
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
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
