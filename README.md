# Extreme_PCP_Scaling_Antarctica

This is the Jupyter notebooks required to reproduce the research published in *International Journal of Climatology*.

This repository is divided in different notebooks that:
  - 0-Download the ERA5 datasets used in this research
  - 1-Compute PCP accumulations for each gridpoint
  - 2-Compute the extreme values for each time interval
  - 3-Compute and plot the scaling law and maps
  - PCPscaling_CaseStudy-Plots for each case study

<!-- More information at: González-Herrero et. al. (2023)
DOI: https://doi.org/10.1038/s43247-022-00450-5 -->

## Versions and dependences

The script consists in a group of Jupyter notebooks programed in python 3.8. The following libraries are necessary:
```
  cdsapi
  os
  glob
  argparse
  time
  sys
  datetime
  netCDF4
  scipy
  numpy
  pandas
  seaborn
  matplotlib  
  cartopy
```
## Complementary dataset

The dataset associated to this research can be found at: https://doi.org/10.5281/zenodo.7538266

## How to cite

If you use or modify this script for your research, please cite as:
González-Herrero, S., Vassalo, F., Bech, J., Gorodetskaya, I. V., Elvira, B., and Justel, A. (2023): Extreme precipitation records in Antarctica. Int. J. Climatol. doi: https://doi.org/10.1002/joc.8020

## Contact

If you have any question, please contact with Sergi at sergi.gonzalez@slf.ch
