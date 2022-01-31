# LCIS_paper
Code, input files and model output data used for figures and analysis in manuscript: 
Harrison et al., Sensitivity of melting, freezing and marine ice beneath Larsen C Ice Shelf to changes in ocean forcing. Submitted to GRL, 2021.

Code and input files to run using the MITgcm model are in the relevant folders. 

All data are in Matlab structures as follows:

Bathymetry, ice base topography, water-column thickness, melt rate, sub-ice velocities and speed, and barotropic streamfunction for the standard run are provided in Brisbourne.mat.

Melt rates, and sub-ice velocities and speed data for the Bedmap2 and Mueller simulations are in Mueller_Bedmap2.mat.

Melt rates for the three additional ocean tempearture cases are in Temperature_sensitivity.mat and marine ice distribution data for each ocean temperature case each have their own Marine_ice_#.mat file, with # = 14 being the -1.4°C case etc. Note that '19' corresponds to the standard run (-1.9°C). Separate marine ice structures are also given for the Mueller and Bedmap2 cases (Marine_ice_Mueller.mat & Marine_ice_Bedmap2.mat).

Tidal_validation.mat holds the model timeseries data presented in the Supplementary materials. 

The barotropic streamfunction for the simulation only forced by tides (no thermodynamic exchange with the ice shelf) is given in Tides_only.mat.

