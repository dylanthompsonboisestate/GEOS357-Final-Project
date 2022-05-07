# Calculating Snow Volume Change Code
## Overview
This code calculates the snow volume from the Bogus Basin area for multiple years. It can easily be adapted to a different area by simply changing the snow depth values and the Landsat 8 images used. Without even changing the snow depth, this program can be useful for simply calculating NDSI and viewing multiple NDSI maps by just changing the directory. A clearer image of what types of figures the code can produce can be seen below. 
## Figure 1: Site Area
![Map](Figures/Map.jpg)

This figure shows the location where the snow volume was calculated. 
## Figure 2: NDSI Change from 2014 to 2020
![NDSIMap](Figures/NDSIMap.png)

This figure shows the NDSI values across the Bogus Basin area calculated from Landsat 8 images. 
## Figure 3: Snow Volume Change
![Volume](Figures/Volume.png)

Using the NDSI values greater than 0.4, an area was determined and multiplied by the snow depth recorded from the Bogus Basin SNOTEL site in order to calculate snow volume. 
## Installation
This code can be used in MatLab R2021A or any later version. This project can be used by cloning the repository to gain access to the structure used in the code, or the .mlx file can be downloaded and the Landsat files can be downloaded and seperated into different folders. 
## Usage 
The Landsat files needed to produce the figures below are not included, but they can be downloaded here [https://earthexplorer.usgs.gov/]. For this project, I used Landsat 8 files from Path 042 and Row 029, but this program will work for any path and row selected. You will need to change the directory in the program to files where each year of Landsat data is stored seperately. To change the snow depth, simple go to line 43 starting with SD and put in the snow depth values you wish to use for calculating snow volume. Enjoy!
-Dylan Thompson
