# LCIS_paper
Model outout data used for figures and analysis in manuscript: 

Harrison et al., Sensitivity of melting, freezing and marine ice beneath Larsen C Ice Shelf to changes in ocean forcing. Submitted to GRL, 2021.

All data are in Matlab structures as follows:

Bathymetry, melt rates, thermal driving, sub-ice velocities water-column thickness, barotropic streamfunction and ice base topography for the standard run are provided in Brisbourne.mat.

Bathymetry, melt rates, and sub-ice velocity data for the Bedmap2 and Mueller simulations are in Mueller_Bedmap2.mat.

Melt rates for the four different tempearture cases are in Temperature_sensitivities.mat and marine ice distribution data for each temperature case each have their own Marine_ice_#.mat file, with # = 14 being the -1.4 degrees C case etc.

Tidal_validation.mat holds the observation and model timeseries data presented in the Supplementary materials. 

The barotropic streamfunction for the simulation only forced by tides (no thermodynamic exchange with the ice shelf) is given in Tides_only.mat.
