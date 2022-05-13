---
layout: page-fullwidth
title: "Design  of numerical ocean simulations at  kilometric resolution to investigate the role of submesoscale oceanic turbulence in the Earth’s climate."
subheadline: ""
teaser: "ReSuMPTiOn project"
header:
    image_fullwidth: "eNATL60_zoom.jpg"
    logoalt: "logo_03_yellow_big.svg"
gallery:
    - image_url: natl60-image_of_the_month_eNATL60.png 
permalink: /expertise/natl60/
breadcrumb: true
---
ReSuMPTiOn is a project  that aims to determine the contribution of kilometric-scale oceanic flow features, known as submesoscale turbulence, in several aspects of the global oceanic circulation known for their importance in regulating the Earth’s climate. To achieve this, realistic numerical simulations of the full 3D oceanic flow in the North Atlantic basin, at ultra-high horizontal and vertical resolution, have been designed and and are currently performed by Ocean Next in close collaboration with the MEOM team at IGE.
As such, the so-called eNATL60 configuration (see technical specifications below), based on the NEMO ocean model, has been developed. eNATL60 simulations are presently being performed on the MareNostrum supercomputer of the Barcelona Supercomputing Center, thanks to a 40 million CPU-hour PRACE allocation granted to Ocean Next in april 2018.

This type of ultrahigh resolution ocean flow simulations (~1 km horizontal grid resolution on 300 vertical levels, with the inclusion of tidal motions), has only been made achievable recently thanks to the advance in HPC capabilities of modern supercomputers. Besides providing the project team and the ocean/climate community with a pioneering dataset for studying the interactions between fine-scale features and the larger-scale components of oceanic flow, the proposed set of simulations will also be used for preparing upcoming satellite missions, including the SWOT altimetry mission. SWOT will provide observations of the surface ocean dynamics at an unprecedented fine-scale resolution. The present project will allow to develop a system ready to prepare, assimilate, interpret, and further expand (e.g. below the surface) the information that will be obtained from SWOT. This new generation of high spatial resolution altimetric satellite observations from the SWOT mission, combined to the set of proposed ground-breaking ocean simulations, is expected to lead to major breakthroughs in our understanding of the roles played by fine-scale ocean turbulence (and tidal motions) in influencing the large-scale ocean circulation, and thereby, the climate system. The simulations of this project will also be used as a testbed for designing the next generation of models for the Copernicus Marine Environment Monitoring Service.

[Click here to see videos on our Vimeo channel.](https://vimeo.com/oceannext/)

{% include gallery %}

### Technical info about NEMO – eNATL60
eNATL60 is a regional configuration of the NEMO (Nucleus for European Modeling of the Ocean) at ultrahigh horizontal and vertical resolution. eNATL60 is the successor and horizontally extended version of NATL60, it spans the North Atlantic from about 6°N up to the polar circle and fully includes the Gulf of Mexico, the Med Sea, and the Black Sea.

* Numerical code: NEMO 3.6
* Horizontal grid: 1/60°, 8354×4729 points, 0.8 km < Δx < 1.6 km
* Vertical grid: 300 levels
* Boundary conditions: GLORYS12 v1 (1/12°, Mercator Ocean)
* Atmospheric forcing: DFS5.2
* Number of processors in parallel required: 18000
* Model time step: 40s
* Model integration speed: 45 minutes for 1 model day

<a class="radius button small" href="{{ site.url }}{{ site.baseurl }}/expertise/">Read also about our other activities ›</a>


