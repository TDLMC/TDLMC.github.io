[Read the Paper](https://arxiv.org/abs/1801.01506)| [How to Submit](submit_example.txt)

## [](#Introduction)Welcome to the Time Delay Lens Modeling Challenge!
Strong gravitational lenses with measured time delay are a powerful tool to measure cosmological parameters, especially the _Hubble constant_ (_H0_). Recent studies show that by combining the likelihoods of the four time-delay strong lensing systems, one can determine _H0_  down to _3%_  precision ([Birrer et al. 2018](https://arxiv.org/abs/1809.01274v1), [Bonvin et al. 2017](https://academic.oup.com/mnras/article-abstract/465/4/4914/2556158?redirectedFrom=fulltext)). Furthermore, the number of time-delay lens systems is growing rapidly, enabling, in principle, the determination of _H0_  to _1%_  precision in the near future. However, as the precision increases it is important to ensure that systematic errors and biases remain subdominant. For this purpose, blind challenges with simulated datasets are a key component in this process. Following the experience of the [_past challenge on time delay_](http://timedelaychallenge.org), where it was shown that time delays can indeed be measured precisely and accurately at the sub-percent level, we now present the “Time Delay Lens Modeling Challenge” (TDLMC).

We aim to assess the present capabilities of lens modeling codes and assumptions and test the level of accuracy of inferred cosmological parameters given realistic mock datasets. We invite scientists to model a set of simulated _Hubble Space Telescope_ (_HST_) observations of _50_  mock lens systems. The systems are organized in rungs, with the complexity and realism increasing going up the ladder. The goal of the challenge is to infer _H0_  for each rung, given the _HST_  images, the time delay, and a stellar velocity dispersion of the deflector, for a fixed background cosmology.

The TDLMC challenge will start with the mock data release on __2018 January 8th__.
The deadline for blind submission is different for each rung. The deadline for Rung0-1 is __2018 September 8__; the deadline for Rung2 is __2019 April 8__ and the one for Rung3 is __2019 September 8__.

# [](#Data-sets)Challenge Rungs

## [](#Rung-0)Rung0

> Rung0 is a training exercise which consists of two lens systems, one two-image (_double_) and one four-image (_quad_) configuration.

>The goal of this rung is to ensure that “Good” Team members understand the format of the data and that no bugs or mistakes could potentially affect the results of the challenge for a specific method.

## [](#Rung-1)Rung1

> Rung1 is meant to be the easiest ladder. The mocks in Rung1 are generated in a similar way as in Rung0, except that we use the images of real galaxies to get realistic surface brightness distribution for the lensed AGN host and the time delays are affected by external convergence.

## [](#Rung-2)Rung2

> Rung2 is meant to test PSF reconstruction features of lensing codes, in addition to the aspects tested in Rung1. For this purpose, we only provide a guess of the PSF but not the one actually used to generate the data.

## [](#Rung-?)Rung3

> Rung3 is the highest level of difficulty in this challenge, and thus the simulations are intended to be the most realistic. In addition to all the complexity we have adopted for Rung1 and Rung2, the observables are generated using massive early-type galaxies selected from numerical cosmological simulations.

[Download data](download.md)

[Read the Paper](https://arxiv.org/abs/1801.01506) |  [How to Submit](submit_example.txt)
