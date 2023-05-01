---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
permalink: "/index.html"
header:
   image_fullwidth: "odc-banner.jpg"
widget1:
  title: "DC concept"
  url: /concept/
  image: odc_frontpage1.png
  text: 'The concept of data challenges is fairly new and originates from the artificial intelligence community. It is now used by [...]'
widget2:
  title: "Projects"
  url: /projects0/
  image: odc_frontpage2.png
  text: 'The efforts made to create these data challenges were only possible thanks to the fundings of several projects [...]'
widget3:
  title: "The ODC group"
  url: /team/
  image: odc_frontpage3.png
  text: 'We are a group of French scientists from different research teams and companies [...]'

#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /team/
  text: Contact the group ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
