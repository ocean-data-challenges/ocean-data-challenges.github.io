---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
permalink: "/index.html"
header:
   image_fullwidth: "gs_w.jpg"
   logoalt: "logo-text.svg"
widget1:
  title: "About datlas"
  url: /about/
  image: outils-collaboratifs-gestion-de-projet_sq.png
  text: 'datlas was created in 2021 in the aim to develop Research & Innovation opportunities and cooperations at the interface between academic research  and operational stakeolders in the domains of Earth & Environnmental sciences. [...]'
widget2:
  title: "Our team"
  url: /team/
  image: grenoble.png
  text: 'We are a team of  scientists based in Grenoble, with complementary  expertises in numerical methods and numerical models applied to Earth data, ranging from observation data to model simulations and outputs.  [...]'
widget3:
  title: "Our expertise"
  url: /expertise/
  image: icesq.png
  text: 'Our on-going activities  are related to the  observation, modelling and forecasting of the ocean and sea ice. They involve both the devlopment of numerical methods for data inversion and processing, and the development of numerical models.  [...]'

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
  url: /contact/
  text: Contact us ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
