# SafeJustEarthSytemsBnd_EnvFlows
***
<font color=red>Title: Safe and Just Earth Systems Boundaries for Surface Water: Hydrologic Alteration Environmental Flows  
Author: Pamela A. Green  
Date: February 16, 2023  

This code was developed between December, 2021 and February, 2023 by Pamela Green, Senior Research Associate, CUNY Advanced Science Research Center, New York, NY under subcontract to Griffith University.  </font>
***

This code represents spatial modelling for development of the safe and just surface water target for Working Group 3 of the Earth Commission for the Earth Commission Long Report and the <i><b>"Safe and Just Earth Systems Boundaries"</b></i> publication. The surface water target includes spatial modelling of the extent of global-scale hydrological alteration of environmental flows.

Being outside the Earth System Boundary is based on the concept of environmental flow stress; defined as an alteration of surface water flow between pristine (non-human impacted) and disturbed (human impacted) conditions that exceed a given threshold. We derived the pristine and disturbed monthly river flow datasets from the WBM water balance model river discharge outputs (Wisser et al. 2010) at 6-minute grid cell resolution using the TerraClimate high resolution data set of monthly climate forcings (Abatzoglou, et al. 2018) for the period 2000-2020. River basin delineation and flow routing configurations are defined by the WBM 6-minute topological river network used to establish local discharge and river flow (Wisser et al. 2010). The pristine and disturbed WBM runs use the same climate forcings for the 2000-2020 time period but only employ human alterations to the water cycle, including water extraction for irrigation and large reservoirs, in the disturbed runs. 

Long-term mean monthly discharge is calculated for the modelled pristine (non-human impacted) and disturbed (human impacted) discharge from the WBM model over the 2000-2020 time domain to determine the extent of altered flow. The analysis is limited to only the perennial or actively flowing river extents by applying a 3mm/yr upstream monthly average runoff exceedance threshold (Fekete et al. 2001) occurring for at least 10 years out of the 2000-2020 time domain. We also mask out upstream headwater areas (smaller than 250km2) that have modelled irrigation depths below the median irrigation depth for small headwater cells (3.6 mm/yr). This mask is applied to eliminate noise in the modelled data associated with very low irrigation and discharge values in headwater grid cells.

This work is part of the Earth Commission which is hosted by Future Earth and is the science component of the Global Commons Alliance. The Global Commons Alliance is a sponsored project of Rockefeller Philanthropy Advisors, with support from Oak Foundation, MAVA, Porticus, Gordon and Betty Moore Foundation, Herlin Foundation and the Global Environment Facility. The Earth Commission is also supported by the Global Challenges Foundation. 

<b>References:</b>

Abatzoglou, John T., Solomon Z. Dobrowski, Sean A. Parks, and Katherine C. Hegewisch. “TerraClimate, a High-Resolution Global Dataset of Monthly Climate and Climatic Water Balance from 1958–2015.” Scientific Data 5, no. 1 (January 9, 2018): 170191. https://doi.org/10.1038/sdata.2017.191.

Center for International Earth Science Information Network - CIESIN - Columbia University. 2018. Gridded Population of the World, Version 4 (GPWv4): Population Density, Revision 11. Palisades, NY: NASA Socioeconomic Data and Applications Center (SEDAC). https://doi.org/10.7927/H49C6VHW.

Fekete, Balázs M., Charles J. Vörösmarty, and Richard B. Lammers. “Scaling Gridded River Networks for Macroscale Hydrology: Development, Analysis, and Control of Error.” Water Resources Research 37, no. 7 (July 2001): 1955–67. https://doi.org/10.1029/2001WR900024.

GRDC (2020): Major River Basins of the World / Global Runoff Data Centre, GRDC. 2nd, rev. ext. ed. Koblenz, Germany: Federal Institute of Hydrology (BfG).

Wisser, D., B. M. Fekete, C. J. Vörösmarty, and A. H. Schumann. “Reconstructing 20th Century Global Hydrography: A Contribution to the Global Terrestrial Network- Hydrology (GTN-H).” Hydrology and Earth System Sciences 14, no. 1 (January 6, 2010): 1–24. https://doi.org/10.5194/hess-14-1-2010.



```markdown
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
```

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

