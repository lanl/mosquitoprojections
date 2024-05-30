# mosquitoprojections
netCDF files of *Aedes* and *Culex* mosquito habitat suitability for 2020 through 2090 in response to global change. 

## Title:
Projections of predominant *Aedes* and *Culex* mosquitoes across North and South America in response to global change

## Authors: 
Morgan E. Gorris<sup>1</sup>, Andrew W. Bartlow<sup>2</sup>, Travis R. Pitts<sup>3,</sup>, Carrie A. Manore<sup>4</sup>

## Affiliations: 
1. Information Systems and Modeling, Los Alamos National Laboratory, Los Alamos, NM, USA
2. Genomics and Bioanalytics, Los Alamos National Laboratory, Los Alamos, NM, USA
3. Intelligence and Emerging Threats Program Office, Los Alamos National Laboratory, Los Alamos, NM, USA
4. Theoretical Biology and Biophysics, Los Alamos National Laboratory, Los Alamos, NM, USA

## Contact information:
Morgan Gorris, mgorris@lanl.gov

# Description: 
This repository contains netCDF files with habitat suitability values from 0-1 for *Aedes* and *Culex* mosquito species across the Americas: *Ae. aegypti**, *Ae. albopictus**, *Cx. erraticus**, *Cx. nigripalpus**, *Cx. pipiens*, *Cx. quinquefasciatus**, *Cx. restuans*, *Cx. salinarius*, and *Cx. tarsalis*. The maps are available for the contemporary time period, 2020, as well as 2050 and 2090. Projections for 2050 and 2090 are for the SSP2 RCP4.5 and SSP5 RCP8.5 global change scenarios. This output is the mean habitat suitability (0-1) averaged across 10 bootstrapped Maxent models.

*Habitat suitability values for these species are available for both North and South America. The remainder are available for only North America. 

Each netCDF file is less than or up to 1.2 MB in size. 

**The paper associated with this dataset is:**  
Gorris, M. E., Bartlow, A. W., Pitts, T. R., Manore, C. A. (2024). Projections of *Aedes* and *Culex* mosquitoes across North and South America in response to climate change. *The Journal of Climate Change and Health*, *17*(100317), https://doi.org/10.1016/j.joclim.2024.100317 

## netCDF files:
Each netCDF files contains the following three variables:<br />
<br />
**longitude:** 1-dimensional array of longitude values  <br />
**latitude:** 1-dimensional array of latitude values<br />
**layer:** 2-dimensional array, the size of latitude by longitude, containing the habitat suitability values from 0-1. <br />

## LA-UR:
This repository is approved for public release under LA-UR-23-29970.
