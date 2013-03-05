wtoolsge
========

Puts WRF NetCDF data onto Google Earth, interactively if Windows; eventually modify input data before WRF runs.

as of 2013-03-04

I am just beginning this project, so please be patient before expecting results. This README is meant to express the intentions for what I am making. The list of features are in order of priority as I currently see them. If you want to help with suggestions, testing, or coding, let me know whether you want your contact information shown in documentation. Since I am making this open source, it seems appropriate to also make it open information about anyone involved, if they want.

This is a followup program for the WTOOLS program I created and made available on my website: www.nusculus.com/wtools


Done Features:

None. Didn't you just read "Please be patient?"


TODO Features:

1) Read WRF (Weather Research and Forecasting) related data and create KML files for Google Earth. The program reads the variables in the selected file. The user pick the variable from a list. The user picks how the variable data is transformed to KML data - values as colored grid cells or as contour lines (e.g. isotachs).

2) If the Google Earth plugin is available, currently only on Windows, WTtoolsGE puts on and takes off the KML data directly in the Google Earth display. Some basic control of the Google Earth interface is also provided.

3) For WRF input data, allow the user to modify the data values and save them to the input files. 

4) Provide additional display options as identified and implemented. Possibilities include wind barbs, vertical cross sections, cloud cover representations, interpolations to fixed heights, etc.

