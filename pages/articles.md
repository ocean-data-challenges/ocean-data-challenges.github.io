---
layout: page
title: ""
meta_title: 
subheadline: ""
teaser: ""
permalink: "/articles/"
header:
   image_fullwidth: "odc-banner.jpg"
breadcrumb: true
---

## <center> <b> Articles </b> </center>

---

Here are listed the published scientific articles related to the data challenges.

---



### [<u>Level 3 SWOT processing</u>](/dc_L3/)
<br> 

<ul>
 {% for datachallenge in site.data.datachallenges_yml %} 
    {% if datachallenge.experiment == "l3_processing"%}
     {% if datachallenge.articles != nill%}
      <li>  <a href="{{ datachallenge.url }}">{{ datachallenge.title }} </a> 
      <ul>
           {% for article in datachallenge.articles %}
             <li> {{ article }} </li>
             <br>
           {% endfor %}
      </ul>    
      </li>
      <br> 
     {% endif %}
    {% endif %} 
 {% endfor %} 
          
</ul>
 
 

### [<u>Level 4 SSH processing</u>](/dc_L4_SSH/)

<br> 

<ul>
 {% for datachallenge in site.data.datachallenges_yml %} 
    {% if datachallenge.experiment == "ssh_mapping"%}
     {% if datachallenge.articles != nill%}
      <li>  <a href="{{ datachallenge.url }}">{{ datachallenge.title }} </a> 
      <ul>
           {% for article in datachallenge.articles %}
             <li> {{ article }} </li>
             <br>
           {% endfor %}
      </ul>    
      </li>
      <br> 
     {% endif %}
    {% endif %} 
 {% endfor %} 
          
</ul>



### [<u>Level 4 currents processing</u>](/dc_L4_Current/)

<br> 

<ul>
 {% for datachallenge in site.data.datachallenges_yml %} 
    {% if datachallenge.experiment == "current_mapping"%}
     {% if datachallenge.articles != nill%}
      <li>  <a href="{{ datachallenge.url }}">{{ datachallenge.title }} </a> 
      <ul>
           {% for article in datachallenge.articles %}
             <li> {{ article }} </li>
             <br>
           {% endfor %}
      </ul>    
      </li>
      <br> 
     {% endif %}
    {% endif %} 
 {% endfor %} 
          
</ul>




--- 

### **<u>Additional articles</u>**
<br>

- Johnson, J. E.; Febvre, Q.; Gorbunova, A.; Metref, S.; Ballarotta, M.; Le Sommer, J.; Fablet, R. OceanBench: The sea surface height edition. NeurIPS. Submitted. 


