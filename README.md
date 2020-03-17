# BLS_Toolbox
### This repository contains three tools for interacting with the Bureau of Labor Statistics site. In particular, it is optimized for the American Time Use Survey dataset. However the tools can be modified to access any data available from the BLS API.

### Due to the large nature of the datafiles, you should download this folder to your github desktop.

This toolbox assumes you have a BLS API key. If you do not, you can get one here: [BLS API KEY](https://www.bls.gov/developers/)

1.  BLS Web Downloader - Tool 1 of 3 for accessing ATUS files - This pulls flat files from the ATUS (American Time Use Survery) estimates website and converts them into a data dictonary that can be used to search for specific series IDs by characteristics.

2. BLS series selector - Tool 2 of 3 for accessing ATUS files - This notebook will allow you to take the dictonary you generated in the BLS Web Scraper and interactivly select demographics to get the series IDs.

3. BLS_API - Tool 3 of 3 for accessing ATUS files - This file takes in the series list you generated in the BLS Series Finder notebook or from the BLS website and downloads the files. It also cleans the files and adds in the demographic data as well as the standard error calculations from the aspects.txt flat file. The aspects.txt file MUST BE DOWNLOADED FROM THE FIRST NOTEBOOK ON YOUR HDD.

Included data - there are some files included as examples in the data directory. However, some files are too large for git. You will need to download them from first notebook. 

4. Experimental File - In the experimental file there are some EDA notebooks in process. These notebooks use matplotlip, seaborn and bokeh. They are not ready for prime-time use, but feel free to poke around!
