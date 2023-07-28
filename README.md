# VIMS-INTERNSHIP

General

Most of the folders are organized with three subfolders: Inputs, Scripts, and Outputs. This allows you to see the data I inputted, how I changed that data, and what the results were. The descriptions below mainly discuss the Outputs. 

Benthos Organized by Group

This folder contains all of the data related to the project where I used bentho data sorted by groups (i.e.. bioturbation and feeding) to create interpolations of how these groups biomass is spread out over the Chesapeake bay. There are graphs for one year and there are animations showing a range of years. There are also graphs showing the amount of biomass that’s contained in each group. 

Chesapeake Bay Benthic Monitoring Program Data

This folder has all of the data combined together from the Chesapeake Bay Benthic Monitoring Program’s website in the subfolder 1ST-ORDER-INTERMEDIATE-FILES. I used the script Combining Data Script.ipynb to combine the data from the website together. The script AccessingDataScript.ipynb is used to access the data stored in the subfolder 1ST-ORDER-INTERMEDIATE-FILES. In order to use the accessing script, you will need to change the code so the location is correct for where the data is being accessed. 

Every year’s data couldn’t be combined using the combining script. This is because the formatting changed for some years (i.e. 2008). 

One thing that’s important to know about the Chesapeake Bay Benthic Monitoring Program is that 2019 was the last year that data was recorded in Virginia. 

If you want to learn more about what columns’ names mean, you can find out by reading the documentation on the website (linked above) under the heading Data Set Documentation. 

.gr3 files from biomass interpolation

This folder has the .gr3 files that will be used as input for the SCHISM model. These files show the interpolated biomass in the Chesapeake Bay for organisms in each feeding/bioturbation group. 

Nodes Sorted by Region for Interpolation

This folder contains the data I used for interpolation. The image regions.png shows the geography each region corresponds to. The dataset REGION-DEPTH-NODES.csv is used as the points on which the interpolation happens. The dataset STATION-REGION-LATLON.csv is used for the input for creating the interpolation function. This dataset is pretty well sorted by region, but it’s not perfect. Some stations are in regions they shouldn’t belong to or are not assigned a region at all. 

Python Notes

This folder contains notes I took during the internship of useful functions from the different python libraries I used. 
