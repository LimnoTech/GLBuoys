# GLBuoys
Source code to run the Great Lakes Buoy network. 

This repository contains a Django created project called "GLOS_buoy_tools.pyproj" created by LimnoTech (https://www.limno.com/) for the Great Lakes Observing System (https://www.glos.us/) to display buoy's real-time data and allow for historical data viewing and downloading from the Great Lakes Observing System. The project was deployed on an Amazon web service T2-small apache server. Initially the project was used to show real-time data from buoys, weather stations, and water quality stations in the Great Lakes. Later a data plotter and exporter tool located in Plotter_export_tools was added to give users the ability to view and download historical data. The plots are generated using the Highcharts library and licenses is required to legally use this project.

Python code was also developed, located in the directory 'DataGen', to download recent weather/water data from GLOS and NDBC as a json cache for quick data retrieval. Code to scrape National Weather Service forecast was also developed. All tokens that reference to Google Tag Manager, Google Maps API, Bing Maps, and Google Maps have been replaced with place holders. 

# License
Documentation is licensed as GNU General Public License v3.0 (GNU GPLv3) (https://choosealicense.com/licenses/gpl-3.0/). 

# Credits
The Great Lakes Buoy Portal is presented by LimnoTech (https://www.limno.com/) for the Great Lakes Observing System (https://www.glos.us/).
