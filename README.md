# Raster_Z-Factor_Calc-ArcPy
ArcGIS Pro script tool &amp; standalone script to calculate the 1:1 z-factor setting for Digital Elevation Models (DEMs), specifically designed for use with extraplanetary datasets. 

Extraplanetary datasets commonly use Geographic Coordinate Systems with vertical units in meters. In these cases there is a mismatch between linear and vertical units, requiring the user to calculate the Z-factor based on the spheroid's semi-major axis and central latitude of a study area DEM. This script automates Z-factor selection. The user inputs a DEM raster file and Z-factor is calculated from the extent of the dataset along with coordinate system metadata. 
