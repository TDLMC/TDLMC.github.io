[back](./)

# Lens Data

Simulated lens data are generated assuming a flat ΛCDM cosmological model with *Ωm = 0.27*, including:

* _HST_ image
  >Eight non-drizzled images with the drizzled image are provided for one lens system, together with the noise map and PSF. Note that [_drizzling_](http://www.stsci.edu/hst/wfpc2/analysis/drizzle.html) introduces correlated noise. This means one needs to boost the noise level to be effectively infinite at central pixels of each AGN image while modeling drizzled image. The noise maps for the images are provided which contain the standard deviation of the noise.
* Time Delay
* Lens Velocity Dispersion
  >An integrated line-of-sight velocity dispersion is provided assuming a square aperture with *1* arcsec on a side and a seeing condition with a full width at half maximum of *0.6* arcsec.
* External Convergence
  >The *kext* are generated using a random Gaussian distribution with *0* and *0.025* as mean value and standard deviation, respectively. This, from the point of view of modeling, one can adopt a prior on kext of *0±0.025*.
  
The non_drizzled images are put in the first layer of the lens sample folder. Drizzled images are put in the folder named "drizzled_image". The other information of the lens could be found in the text file named "lens_info_for_Good_team.txt". 

_Enjoy the data:_

[**Download Rung0**](data/rung0.tar.gz) [*True parameter for Rung0*](data/rung0_open_box.tar.gz)

[**Download Rung1**](data/rung1.tar.gz) [*Rung1 open box*](data/rung1_open_box.zip)

   >The oversampled PSF as used in the simulation are provided; the pixel size is *0.13/4=0.0325 arcsec*:
   >
   >  [**Download oversampled PSF for Rung0-1**](data/oversampled_PSF.fits)


[**Download Rung2**](data/rung2.tar.gz)

[**Download Rung3**](data/rung3.tar.gz)

[back](./)
