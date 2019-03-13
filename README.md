# Sectorcoupling-Loadshapegenerator
This loadshapegenerator is intendet to manipulate an existing baseload of multiple loads by adding loadshapes of heatpumps, battery electric vehicles, photovoltaik and electric home storages.
The baseloads are imported from a csv-file into a pandas dataframe. The head of the csv-file contains the name of the load while the first column contains the timesteps of the loadshapes.

The folder literature contains some references to the calculations made by the loadshape generator.
"Kapitel_5_Lastprofilgenerator.pdf" contains a detailled explanation of the loadshape generator, but it is in German for now. 
