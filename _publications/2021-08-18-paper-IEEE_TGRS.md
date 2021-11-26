---
title: "Rethinking Satellite Data Merging: From Averaging to SNR Optimization"
collection: publications
permalink: /publication/2021-08-18-paper-IEEE_TGRS
excerpt: Improved data merging method.
date: 2021-03-23
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
paperurl: https://ieeexplore.ieee.org/document/9531937
citation: 'Kim, S., Sharma, A., Liu, Y., Young S.I. (2021). Rethinking Satellite Data Merging: From Averaging to SNR Optimization, <i>IEEE Transactions on Geoscience and Remote Sensing</i>, Early Access, 1-15'
---
## Abstract
Merging of multiple satellite datasets is a simple yet effective way to reduce prediction error. However, most merging methods for satellite data today are based on weighted averaging first proposed in 1969 for economic forecasting, which does not provide optimal outcomes when applied to satellite data. If our aim is to produce a merged data product that minimizes the prediction errors against a prediction target, there is no reason to insist that the merged product be an average of the parent datasets. A more disciplined approach based on mathematical optimization would be to minimize prediction errors. However, formulating merging as an optimization problem is insufficient by itself as the statistics needed for optimization, e.g. signal-to-noise ratio (SNR) of parent products, are often unavailable in practice and must be estimated jointly. In this paper, we address both of these problems for data merging. We first formulate optimal merging of satellite data as a SNR optimization (SNR-opt), and propose an estimation method to jointly estimate the required SNRs. This SNR-based approach has a natural interpretation as a multi-input single-output Wiener filter. Through extensive experimental validation on three global- scale satellite-derived soil moisture and land surface temperature products, we demonstrate that our SNR optimization significantly improves merging results over weighted averaging schemes.
<br/><img src='/images/SNR_opt.jpg' width="90%" height="90%">