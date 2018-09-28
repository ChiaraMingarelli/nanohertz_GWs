# nanohertz_GWs: How to create your own nanohertz gravitational-wave universe.

This repo contains Jupyter notebooks, accompanying files etc.., to reproduce results in Mingarelli et al. (2017). 
Please cite Mingarelli et al. (2017) when using this code, as well as 10.5281/zenodo.838712, [![DOI](https://zenodo.org/badge/90664185.svg)](https://zenodo.org/badge/latestdoi/90664185) .

There are 7 directories in this repository: codes, detectedSkies, detection_curves, galaxy_data, gw_skies, healpix_maps and scatter_maps.

## Brief description of directories

### codes:
Here you will find ipython notebooks which walk you through creating gravitational wave skies, with each step clearly indicated in the file name. Example output is given in the example_sky directory.

### detectedSkies:
when a GW sky contains a detectable GW source, it is saved to a text file in this directory. An example of what this file looks like is given here, in detected_skies.txt

### detection_curves:
These are the predicted IPTA curves for 15, 20 and 25 year datasets. Each file has a descriptive name. For example, cw_simulation_Ared_0_dp_0.5_fap_0.001_T_15.txt is the continuous GW wave simulation with zero red noise (Ared_0), a 50% detection probability (dp_0.5), false alarm probability of 0.001 (fap_0.001) for a 15 year dataset (T_15).
The code used to make these curves was developed by Justin Ellis, and is available here, https://github.com/jellis18/time_to_detection.

### galaxy_data
This contains the galaxy catalog made from 2MASS, together with a list of galaxies which had measured SMBHs. These masses are used instead of M-Mbulge.

### gw_skies:
Here we provide a few hundred GW skies as an example of what the code output looks like.

### healpix_maps:
Fits files for 87 GW frequencies

### scatter_maps:
The same information that was in the fits files, but here in a .dat file as an alternative option.
