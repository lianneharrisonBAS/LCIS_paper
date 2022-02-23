# LCIS_paper
Code, input files and some model output data used for figures and analysis in manuscript: 
Harrison, L. C., Holland, P. R., Heywood, K. J., Nicholls, K. W., & Brisbourne, A. M. (2022). Sensitivity of melting, freezing and marine ice beneath Larsen C Ice Shelf to changes in ocean forcing. Geophysical Research Letters, 49, e2021GL096914. https://doi.org/10.1029/2021GL096914

Code and input files to run using the MITgcm model are in the relevant folders. 

Model output data are in Matlab structures as follows:

Bathymetry, ice base topography, water-column thickness, melt rate, sub-ice velocities and speed, and barotropic streamfunction for the standard run are provided in Brisbourne.mat.

Melt rates, and sub-ice velocities and speed data for the Bedmap2 and Mueller simulations are in Mueller_Bedmap2.mat.

Melt rates for the three additional ocean tempearture cases are in Temperature_sensitivity.mat.

Tidal_validation.mat holds the model timeseries data presented in the Supplementary materials. 

The barotropic streamfunction for the simulation only forced by tides (no thermodynamic exchange with the ice shelf) is given in Tides_only.mat.

These data and all other data underlying the figures and analysis of the paper (including marine ice fields) are available in netCDF form from the UK Polar Data Centre: https://doi.org/10.5285/A54C795C-E0EE-49CB-99DD-BEFBDC4A70F0
