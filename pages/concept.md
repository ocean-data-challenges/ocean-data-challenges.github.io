---
layout: page
title: ""
meta_title: 
subheadline: ""
teaser: ""
permalink: "/concept/"
header:
   image_fullwidth: "odc-banner.jpg"
breadcrumb: true
---

## <center> Concept of the ocean data challenges </center>


---
<br>
<div style="text-align: justify"> 
The concept of data challenges is fairly new and originates from the artificial intelligence community. It is now used by many instances to address targeted problems. The principle is straightforward: a problem of interest is introduced, adequately described and a set of data is provided to the participants in order to solve it. The goal is then to find the most accurate solution according to predefined metrics. Data challenges are often proposed by companies or entities to obtain a unique solution, the best solution, to their problem.
</div>
 

<center>
<img src="/images/odc-logo-white1.jpg" />
</center>
 

<div style="text-align: justify">
In our case, Ocean Data Challenges advocates for a more collaborative data challenge where the problem is co-defined in conjunction with the participants. Also, the algorithms used by the participants are open and shared. The results of all the methods are then discussed and analyzed as a group. This way, collaborative data challenges are appropriate platforms to gather forces and unite scientific groups. Moreover, in this configuration, the outcome of the challenges is not only the best solution to a problem but also a more nuanced and rich scientific understanding.
</div>

 

<br> 

## <center> Historic </center>


---

<br> 

<div style="text-align: justify">
The journey of collaborative data challenges (DCs) in oceanography commenced in 2020 with the pioneering efforts of the BOOST-SWOT project, funded by the French ANR and led by Emmanuel Cosme (IGE). The inaugural DC focused on altimetric mapping within the Gulfstream region, utilizing a synthetic system experiment with artificial data from the NATL60 oceanic simulation. This initiative, involving the IGE lab, CLS company, and the IMT-Atlantique lab, laid the foundation for collaborative endeavors aimed at enhancing oceanographic products.
</div>


<br> 

<div style="text-align: justify">
Building on the success of the first DC, a subsequent challenge swiftly followed in 2021, transitioning from synthetic to real altimetric data, albeit limited to conventional altimeters. This iterative process, still under the auspices of the BOOST-SWOT project, marked a progression towards real-world applications, further refining altimetric mapping methodologies.
</div>


<br> 

<div style="text-align: justify">
As BOOST-SWOT concluded its activities post-2021, the baton of collaborative innovation was passed to a new wave of projects (CMEMS, CNES, ESA ...). Spearheaded by the IGE and CLS, alongside the emerging Datlas company based in Grenoble, these endeavors expanded the scope of DCs, attracting diverse scientific groups to participate. With the aim of continually improving oceanographic products, these projects ushered in an era of increased collaboration, inviting broader engagement from the scientific community.
</div>




<br> 

## <center> List of available data challenges </center>


---

<br> 

### [<u>Level 3 SWOT processing</u>](/dc_L3/)
<br> 

<ul>
 {% for datachallenge in site.data.datachallenges_yml %} 
    {% if datachallenge.experiment == "l3_processing"%}
      <li>  <a href="{{ datachallenge.url }}">{{ datachallenge.title }} </a> <br>
          <b><i> By {{ datachallenge.author }} </i> </b> 
      <div style="text-align: justify">
       {{ datachallenge.text }} 
      </div>
      </li>
      <br> 
    {% endif %} 
 {% endfor %} 
          
</ul>
 
 

### [<u>Level 4 SSH processing</u>](/dc_L4_SSH/)

<br> 

<ul>
 {% for datachallenge in site.data.datachallenges_yml %} 
    {% if datachallenge.experiment == "ssh_mapping"%}
      <li>  <a href="{{ datachallenge.url }}">{{ datachallenge.title }} </a> <br>
          <b><i> By {{ datachallenge.author }} </i> </b>
      <div style="text-align: justify">
       {{ datachallenge.text }} 
      </div>
      </li>
      <br> 
    {% endif %} 
 {% endfor %} 
          
</ul>



### [<u>Level 4 currents processing</u>](/dc_L4_Current/)

<br> 

<ul>
 {% for datachallenge in site.data.datachallenges_yml %} 
    {% if datachallenge.experiment == "current_mapping"%}
      <li>  <a href="{{ datachallenge.url }}">{{ datachallenge.title }} </a> <br>
          <b><i> By {{ datachallenge.author }} </i> </b>
      <div style="text-align: justify">
       {{ datachallenge.text }} 
      </div>
      </li>
      <br> 
    {% endif %} 
 {% endfor %} 
          
</ul>




