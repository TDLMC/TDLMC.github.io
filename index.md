---
layout: default
---
[Read the Paper](https://www.google.com)

[How to Submit](another-page)

# [](#Introduction)Project Introduction
Strong gravitational lens with measured time delay is becoming an increasingly powerful tool to measure cosmological parameters, especially the _Hubble constant_ (_H0_). Recent studies show that by combining just three multiply-imaged AGN systems, one can determine _H0_ to _3.8%_ precision. Furthermore, the number of time-delay lens systems is growing rapidly, enabling, in principle, the determination of _H0_ to _1%_ precision in the near future. However, as the precision increases it is important to ensure that systematic errors and biases remain subdominant. For this purpose, challenges with simulated datasets are a key component in this process. Following the experience of the past [challenge on time delay](http://timedelaychallenge.org), where it was shown that time delays can indeed be measured precisely and accurately at the sub-percent level, we now present the “Time Delay Lens Modeling Challenge” (TDLMC).

The goal of this challenge is to assess the present capabilities of lens modeling codes and assumptions and test the level of accuracy of inferred cosmological parameters given realistic mock datasets. We invite scientists to model a set of simulated _Hubble Space Telescope_ (_HST_) observations of _50_ mock lens systems. The systems are organized in rungs, with the complexity and realism increasing going up the ladder. The goal of the challenge is to infer _H0_ for each rung, given the _HST_ images, the time delay, and a stellar velocity dispersion of the deflector, for a fixed background cosmology.

The TDLMC challenge will start with the mock data release on __2018 January 8th__, with a deadline for blind submission of __2018 August 8th__. 

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

