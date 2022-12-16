# DFDE_manuscript_Patacca_etal2022
This repository contains the codes used for the analysis and producing the main figures of the paper: 
Significant increase in natural disturbance impacts on European forests since 1950. 
Patacca et al., 2022.

The link to the raw data contained in the Database of Forest Disturbance in Europe (DFDE) is: https://dfde.efi.int/db/dfde_app.php

The files called "Figure_#", where # is the number of the figures, contain the code used to produce the figures correspondent to the same # in the main text of the manuscript.

The file called "RF_example" contains an example of the code used to produce, train and apply the (80) random forest algorithms used in the gap-filling procedure explained in the main text of the manuscript. 

The file called "disturbance_timeseries_database.xlsx" contains for each disturbance driver, the country level damage values of:
-The cleaned time-series we constructed by processing raw reported data from the DFDE; 
-The time-series gap-filled based on the reported data; 
-The time-series gap-filled based on expert-interpretation; 
-The labelling of the expert for each time-series per disturbance driver and country.

Please cite the data as: Patacca, M., Lindner, M., Lucas-Borja, M. E., Cordonnier, T., Fidej, G., Gardiner, B., Hauf, Y., Jasinevičius, G., Labonne, S., Linkevičius, E., Mahnken, M., Milanovic, S., Nabuurs, G.-J., Nagel, T. A., Nikinmaa, L., Panyatov, M., Bercak, R., Seidl, R., Ostrogović Sever, M. Z. ... Schelhaas, M.-J. (2022). Significant increase in natural disturbance impacts on European forests since 1950. Global Change Biology, 00, 1–18. https://doi.org/10.1111/gcb.16531

Data DOI: 10.5281/zenodo.7319179
