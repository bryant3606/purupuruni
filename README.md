# purupuruni
Data and software repository 

The software, complete data set and inversion results are released as a companion to
Volcano-tectonic interaction in the Central Andes: seismic sequences and uplift in the Purupuruni-Casiri volcanic complex
by
K. Vargas, J. C. Villegas-Lanza, M. Battaglia and P. Euillades

For information about the InSAR data set, please contact kvargas@igp.gob.pe
For information about the modeling software, please contact mbattaglia@usgs.gov

# Description
We used the open-source software dMODELS (Battaglia et al., 2013) to infer the location, geometry and slip of the fault segments that ruptured near Purupuruni and Casiri volcanoes. This software is based on analytical models of dislocation sources (Okada, 1985) to reproduce the surface deformation in an elastic, flat half space. The inverse models implement a weighted least-squares algorithm combined with a random search grid to infer the minimum of the penalty function, the chi-square per degree of freedom (Bergstra and Bengio, 2012). Using rectangular dislocations with a constant slip to model the faults is a major simplification, although it may lead to reasonable first-order solutions (Lisowski, 2007).

# Notes:
The scripts were written in Matlab v 2023b and require the following Matlab toolboxes:
(a) Optimization toolbox (mandatory, required by the function fmincon in the inversion scripts)

# Project status
Completed

# INFORMATION ABOUT PURUPURUNI AND CASIRI
Purupuruni and Casiri are a group of lava domes located in the Vilacota Maure Conservation Area, a remote, desertic area in southern Peru. Although no historical eruptions are known, the volcanoes are considered potentially active, and present various hydrothermal features and hot springs. A significant unrest, characterized by deformation and seismic activity, was observed in the area between the April 2020 and January 2022. Because of the remote location, difficulty of access and desertic landscape, we used satellite geodesy to monitor the local tectonic and volcanic deformation. We were able to identify two different deformation processes. A large-scale uplift that began shortly before the earthquake sequences and ceased a few months after the end of the seismic unrest, and co-seismic deformation associated with motion along the local system of normal faults. The co-seismic deformation occurred in four distinct fault segments and with different deformation rates. The possible origin of this large-scale uplift could be the intrusions of small batches of magma from a deep reservoir feeding the local volcanoes, which would have caused the re-activation of the normal faults.

# License
Unless otherwise noted, this project is in the public domain in the United
States because it contains materials that originally came from the United
States Geological Survey, an agency of the United States Department of
Interior. For more information, see the official USGS copyright policy at
https://www.usgs.gov/information-policies-and-instructions/copyrights-and-credits
Additionally, we waive copyright and related rights in the work
worldwide through the CC0 1.0 Universal public domain dedication.
