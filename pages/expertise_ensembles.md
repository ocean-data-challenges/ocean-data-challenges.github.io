---
layout: page-fullwidth
title: "Learning from large-ensemble ocean simulations to better interpret satellite and in-situ ocean data."
subheadline: ""
teaser: ""
header:
    image_fullwidth: "earth20161122_blue.jpg"
    logoalt: "logo_03_yellow_big.svg"
permalink: /expertise/ensembles/
breadcrumb: true
---
Over the last decades, altimeter and other satellite and in-situ ocean observations have provided crucial information to increase our knowledge of the global oceanic state, its variability, and long-term changes. Comparing observations to ocean numerical simulations is a routinely-used approach to either validate models,  calibrate new observation systems, or investigate physical processes and mechanisms.  But such comparison requires some knowledge of the different types of uncertainties attached to these different kind of data.
Given the chaotic, non-linear nature of the ocean system, numerical ocean models in the turbulent regime are highly sensitive to initial conditions and spontaneously generate a chaotic intrinsic variability that has recently been shown to be significant even on interannual and longer time-scale,  and on entire basins  (e.g. Penduff et al, 2011, Serazin et al, 2015, Leroux et al 2017).

__Performing ensemble simulations is a way to take into account this intrinsic uncertainty, inherent to the ocean circulation, by sampling a range of possible realisations  of equal likelihood of the ocean state  evolution.
In other words, it means that simulations from ocean numerical models must come with an "error bar" in the same way  as satellite/in-situ observations are provided with error of different kind (instrument, post-processing, etc). The model "error bar" can be estimated via ensemble simulations.__

At Ocean Next, we develop such probabilistic approaches, based on large-ensemble eddy-permitting ocean simulations. Our goal is to better quantify and characterize the model uncertainty related to the intrinsic variability of the ocean, and to provide useful information to better compare to and interpret satellite and in-situ ocean data. It includes  a quantification of the chaotic variability and a better characterization of the locations, depth, temporal and spatial scales that are the most affected by a chaotic behaviour in models, and which are thus  affected by  the largest uncertainty in any comparison with satellite or in-situ observations.

---
[![Fig1]({{ site.urlimg }}occi.png "Fig1")]({{ site.urlimg }}occi.png)
_Fig1: This scheme presents the setup of a large-ensemble simulation of 50 members performed and analyzed by Ocean Next in collaboration with  IGE/MEOM, Grenoble. It has been designed to take into account the model uncertainty coming  from the initial conditions and the fact that the simulated ocean has a turbulent/chaotic behavior. Instead of a deterministic description of the ocean state with time, the ensemble simulation provides a probabilistic description of the ocean state (i.e. a statistical distribution) at each time step. It allows for the detection of local non-gaussian behaviors  for example (see Fig.2). For more information on this ensemble simulation, see [Bessière et al, 2017](Geosci.Model Dev., 10, 1091-1106, doi:10.5194/gmd-10-1091-2017 Development of a probabilistic ocean modelling system based on NEMO 3.5: application at eddying resolution)._

---
[![Fig2]({{ site.urlimg }}GMocci.png "Fig2")]({{ site.urlimg }}GMocci.png)
_Fig2: The probabilistic description of the ocean state  allows for the detection of areas where the ocean has a strongly non-gaussian behavior, such as in the Gulf of Mexico (Figure), where a bi-modal distribution is detected in the loop-current, and an asymmetrical distribution is detected further in the Gulf, along the trajectory of the eddies released by the loop-current with an irregular frequency and then advected westward in the Gulf. The figure above shows the sea-level-height  (SSH) distribution of the 50 members of the large-ensemble simulation, and compare with the AVISO satellite observation time-series. The model spread and its variations with time give an indication of the range of values (and probability) in which the satellite observations are expected to fall at each location._

<a class="radius button small" href="{{ site.url }}{{ site.baseurl }}/expertise/">Read also about our other activities ›</a>


A list of related publications can be found [here](http://meom-group.github.io/projects/occiput/) 