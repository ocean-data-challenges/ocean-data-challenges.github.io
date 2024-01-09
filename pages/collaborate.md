---
layout: page
title: ""
meta_title: 
subheadline: ""
teaser: ""
permalink: "/collaborate/"
header:
   image_fullwidth: "odc-banner.jpg"
breadcrumb: true
---

## <center> <b> Collaborate to ODC and propose your own data challenge </b> </center>


---
 
 
 
### To have your data challenge appear on the ODC website, nothing simpler ! 

<br> 

- 1) Fill the informations related to your data challenge into a yaml format

- 2) Provide us with these info

<br> 

#### 1) Fill the informations related to your data challenge into a yaml format: 

<br> 

<pre>
  <code>
    - id: "your_DC_id"
      title: "your_DC_name"
      creationdate: 2024 
      experiment: "your_DC_experiment_type"
      region: "your_DC_region"
      url: https://your_DC.github.io
      url-readthedocs: https://your_DC.readthedocs.io
      url-opendap: https://your_DC_data.html
      image: your_image.png
      text: 'Description'
      articles: 
          - 'Article 1'    
          - 'Article 2'       
  </code>
</pre>

To respect this template, you need to: 

- choose any id you want (hopefully one that does not already exist),
- provide the title/name of your DC (don't make it too long), 
- choose **your_DC_experiment_type** from ```"l3_processing"```, ```"ssh_mapping"``` and ```"current_mapping"```, 
- choose **your_DC_region** from the existing regions (```"North Atlantic"```, ```"Gulfstream"```, ```"Mediterranean"```, ```"California"```, ```"Agulhas"```)
- provide at least the github url of your DC in ```'url:'```
- you'll need to include your illustration image in 'images/' repository at the root of the website folder,
- provide some brief description and article references linked to your DC if there are any. 


Note, that if either **your_DC_experiment_type** or **your_DC_region** do not correspond to any proposed option, you'll have to [contact us](/contacts/) so we setup a specific section in the website for your data challenge. 

<p>An example from the first 2020 data challenge is:</p>
<pre>
  <code>
    - id: DC2020a 
      title: "2020-DC SSH Mapping in the Gulf Stream OSSE"
      creationdate: 2020
      widgetname: 'widget2020a'
      experiment: "ssh_mapping"
      region: "Gulfstream"
      url: https://ocean-data-challenges.github.io/dc_2020a/
      url-opendap: https://ige-meom-opendap.univ-grenoble-alpes.fr/thredds/catalog/meomopendap/extract/MEOM/OCEAN_DATA_CHALLENGES/2020a_SSH_mapping_NATL60/catalog.html
      image: DC_2020a.png
      text: 'The goal is to investigate how to best reconstruct sequences of Sea Surface Height (SSH) maps artificial nadir and SWOT satellite altimetry observations. '
      articles: 
          - 'Le Guillou, F.; Metref, S.; Cosme, E.; Ubelmann, C.; Ballarotta, M.; Le Sommer, J.; Verron, J. Mapping Altimetry in the Forthcoming SWOT Era by Back-and-Forth Nudging a One-Layer Quasigeostrophic Model. J. Atmos. Oceanic Technol. 2021, 38, 697–710. https://doi.org/10.1175/JTECH-D-20-0104.1'
          - 'Beauchamp, M.; Febvre, Q.; Georgenthum, H.; Fablet, R. 4DVarNet-SSH: end-to-end learning of variational interpolation schemes for nadir and wide-swath satellite altimetry. Geoscientific Model Development Discussions. 2022, 1-37. https://doi.org/10.5194/gmd-16-2119-2023'
          - 'Febvre, Q.; Fablet, R.; Le Sommer, J.; Ubelmann, C. Joint Calibration and Mapping of Satellite Altimetry Data Using Trainable Variational Models. ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Singapore, Singapore, 2022, pp. 1536-1540. https://doi.org/10.1109/ICASSP43922.2022.9746889'         
  </code>
</pre>


Here, the url-readthedocs is not provided since the 2020 DC does not have an associated readthedocs website. 


#### 2) Provide us with these info 

<br> 

To do so, you can either: 

- clone the [website github repo](https://github.com/ocean-data-challenges/ocean-data-challenges.github.io), add your yaml input in the ```_data/datachallenges_yml.yml``` file and your illustation image in ```images/``` and make a pull request of these modifications.

- contact us directly at [Contacts](/contacts/) and send us directly these info, we'll update the website for you.  

