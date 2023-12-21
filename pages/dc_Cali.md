---
layout: pagepluswidgets_dc
title: DC - Californian current 
teaser: ""
breadcrumb: true
permalink: "/dc_Cali/"
header:
   image_fullwidth: "odc-banner.jpg" 

widget2023a:
  title: "2023b High frequency dynamic mapping data challenge in California Xover"
  url: https://ocean-data-challenges.github.io/dc_2023b/
  image: DC_2023b.png
  text: 'A challenge on mapping high frequency SSH with artificial SWOT and nadir data in the Californian SWOT X-over created by Datlas and MEOM-IGE. [...]'
 
--- 


# Data challenges in the Californian current 


</br>
<ul>
{% for datachallenge in site.data.datachallenges_yml %}
   {% if datachallenge.creationdate == 2024 %}
     <li> <b> <a href={{ datachallenge.url-readthedocs }}>{{ datachallenge.region }}</a> </b></li>
   {% endif %}
{% endfor %}
</ul>



---



