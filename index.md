---
layout: default
---
[Read the Paper](https://www.google.com)

[How to Submit](another-page).

# [](#Introduction)Project Introduction

Strong lensing time-delay lens is becoming an increasingly powerful tool to measure cosmological parameters, especially the Hubble constant H{_0}. Recent studies show that by combining just three multiply-imaged quasars, one can determine $H_{0}$ to 3.8% precision. Furthermore, the number of time-delay lens systems is growing rapidly, enabling in principle the determination of the H0 to 1% precision in the near future. However, as the precision increases it is important to ensure that the accuracy is also high, i.e. that systematic errors and biases remain subdominant. Challenges on simulated datasets are a key component in this process. Following on the experience of the past time delay challenge, where it was shown that time delays can indeed be measured precisely and accurately at the sub-percent level, we now present the “Time Delay Lens Modeling Challenge”. The goal of the challenge is to assess the present capabilities of lens modeling codes and assumptions and test the level of accuracy of inferred cosmological parameters given realistic datasets. We invite scientists to model a set of simulated Hubble Space Telescope (HST) observations of 50 mock lens systems. The goal of the challenge is to infer H0 for each rung, given the HST images, the time delay, and a stellar velocity dispersion of the deflector, for a fixed background cosmology. The systems are organized in rungs, with the complexity and realism increasing going up the ladder. The TDLMC challenge will start with the mock data release on 2017 December 15st, with a deadline for blind submission of 2018 July 15. This first paper gives an overview of the challenge including the data design, and a set of metrics to quantify the modeling performance and challenge details.

# [](#Data-sets)Data Sets
_Enjoy the data fun_

## [](#Rung-0)Rung-0

> Rung0 is a training exercise which consists of two lensed systems, one two-image (double) and one four-image (quad)configuration. The goal of this rung is to ensure that “Good” Team members understand the format of the data and that no bug/mistake could potentially false the results of the challenge for a specific method.

[Link to the fits file](data/test_data.png)

## [](#Rung-1)Rung-1

> This rung is meant to be the easiest one of the ladder. Thus, the mocks in Rung1 are generated in a similar way as in Rung0, except that we use a more realistic surface brightness distribution for the lensed AGN host and the time delays are affected by external convergence.

[Link to the fits file](data/test_data.png)

## [](#Rung-2)Rung-2

> Rung2 is meant to test PSF reconstruction features of lensing codes, in addition to the aspects tested in Rung1. For this purpose, we only provide a guess of the PSF but not the one actually used to generate the data.

[Link to the fits file](data/test_data.png)

## [](#Rung-3)Rung-3

> Rung3 is the highest level in this challenge, and thus the simulations are intended to be the most realistic. In addition to all the complexity we have adopted for Rung1 and Rung2, the observables are generated using massive early-type galaxies selected from numerical cosmological simulations.


[Link to the fits file](data/test_data.png)

