---
title: "Dynamic Linear Combination"
excerpt: "MATLAB codes for dynamic linear combination of soil moisture datasets (Kim et al.,2016) 
collection: software
---
## Abstract
Soil moisture is an important variable in the coupled hydrologic and climate system. In recent years, microwave-based soil moisture products have been shown to be a viable alternative to in situ measurements. A popular way to measure the performance of soil moisture products is to calculate the temporal correlation coefficient (R) against in situ measurements or other appropriate reference datasets. In this study, an existing linear combination method improving R was modified to allow for a non-static or nonstationary model combination as the basis for improving remotely-sensed surface soil moisture. Previous research had noted that two soil moisture products retrieved using the Japan Aerospace Exploration Agency (JAXA) and Land Parameter Retrieval Model (LPRM) algorithms from the same Advanced Microwave Scanning Radiometer 2 (AMSR2) sensor are spatially complementary in terms of R against a suitable reference over a fixed period. Accordingly, a linear combination was proposed to maximize R using a set of spatially-varying, but temporally-fixed weights. Even though this approach showed promising results, there was room for further improvements, in particular using non-static or dynamic weights that take account of the time-varying nature of the combination algorithm being approximated. The dynamic weighting was achieved by using a moving window. A number of different window sizes was investigated. The optimal weighting factors were determined for the data lying within the moving window and then used to dynamically combine the two parent products. We show improved performance for the dynamically-combined product over the static linear combination. Generally, shorter time windows outperform the static approach, and a 60-day time window is suggested to be the optimum. Results were validated against in situ measurements collected from 124 stations over different continents. The mean R of the dynamically-combined products was found to be 0.57 and 0.62 for the cases using the European Centre for Medium-Range Weather Forecasts Reanalysis-Interim (ERA-Interim) and Modern-Era Retrospective Analysis for Research and Applications Land (MERRA-Land) reanalysis products as the reference, respectively, outperforming the statically-combined products (0.55 and 0.54).   
<br/><img src='/images/dynamicComb.jpg' width="90%" height="90%">

## Download

You can download the codes and sample data from [Hydrology@UNSW](https://www.hydrology.unsw.edu.au/download/software/dynamic-linear-combination).

## Citation
Kim, S., Parinussa, R. M., Liu, Y. Y., Johnson, F. M., & Sharma, A. (2016). Merging alternate remotely-sensed soil moisture retrievals using a non-static model combination approach. <i>Remote Sensing</i>, 8(6), 518.
