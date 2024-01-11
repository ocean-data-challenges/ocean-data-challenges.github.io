---
layout: page
title: ""
meta_title: 
subheadline: ""
teaser: ""
permalink: "/datasets/"
header:
   image_fullwidth: "odc-banner.jpg"
breadcrumb: true
---

## <center> <b> Available datasets </b> </center>


---
 
<center>
<table>
  <thead>
    <tr>
      <th><center>Data Challenge</center></th>
      <th><center>Datasets</center></th>
      <th><center>  Documentation  </center></th>
    </tr>
  </thead>
  <tbody>
        {% for datachallenge in site.data.datachallenges_yml %} 
          <tr> 
             <td> <b>  {{ datachallenge.title }} </b></td> 
             <td> {% if datachallenge.url-opendap == nil %} 
                 <i><center>Upon request</center></i> 
                  {% else %}
                 <a href="{{ datachallenge.url-opendap }}"><center>opendap</center></a> 
                  {% endif %}
             </td>
             <td> {% if datachallenge.url-readthedocs == nil %} 
                    <a href="{{ datachallenge.url }}"><center>github</center></a>
                  {% else %}
                    <a href="{{ datachallenge.url-readthedocs }}"><center>readthedocs</center></a>
                  {% endif %}
              
             </td> 
          </tr>
        {% endfor %} 
      
  </tbody>
</table>
</center>
