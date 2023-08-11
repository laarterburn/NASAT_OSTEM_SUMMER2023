# NASAT_OSTEM_SUMMER2023
Code from the NASA GSFC internship summer 2023


Explanation of files
Animated_plots
All files in folder: These are the videos I put together of all of the aeronet, geoleo, and epa aqs plots I made using the hourly data from June 1, 2023 to June 12, 2023. The geoleo video and the aeronet video were made from the code in the animating_plots.ipynb in the extras folder. 
Extras
Code613_Presentation_Linda_Arterburn.pptx: My presentation I gave for the 613/614 and the code 600 presentation.
Animating_plots.ipynb: The code I used to animate the plots for aeronet and geoleo data. For this code to work you have to make sure you number your plots so it will organize them correctly. This method is very hit or miss. 
GeoLeo
GEOLEO_ANALYSIS.ipynb: These are some plots from the geoleo data that Rob gave me. I changed the latitude and longitude to fit just the coordinates of the wildfire and then I plotted everything
OpenAQ
OpenAQ_getting_csvs.ipynb: This was made from the OpenAQ_Demo.ipynb to just pull and save csv files
OpenAQ_Demo: Carl Mailing’s notebook that he made to get all of the monitor data from OpenAQ and plot the monitors as well as make timeseries using the data
OpenAQ_only_EPA_carls_code.ipynb: This notebook is isolated code from Carl_Master_notebook.ipynb that takes the section out wso you can access ONLY EPA AQS data. 
Carl_master_notebook: this is Carl’s large notebook where you can access data from GEOS-CF, TROPOMI, EPA Data, and VIIRS data (and more)
OpenAQ_PurpleAir_locations_and_measurements.ipynb: This notebook was given to me from Gabe Fosse at OpenAQ. It gets the PurpleAir data (or any systems data depending on what code you put into the system for which air quality network) and it has a limit of 1000 monitors but you can see where they all are in the USA. I need to go look at this code and edit it still to see if I can get the coordinates to show for all of the monitor data. I will be editing this code to get the proper formatting to also get the variables needed for correction factors from the Pm2.5 monitors. 
Aeronet
Pawans_allinone_map_aeronet_data.ipynb: The exact notebook Pawan made to access aeronet data. How I got my aeronet plotds/ data.
Kriging
Bonne_kml_example.ipynb: Bonne’s notebook she gave me to work with for Kriging. I am asking her more questions on this before I go in and update anything/ put in comments.
Bonne_kml_update.ipynb: An upsate to her notebook that I have not looked at entirely.
Pm_pykrige.ipynb: The notebook I have been experimenting with to krige the PM2.5 plots and the aeronet aod plots. I need to ask bonne questions about all of this. 
Data_for_plots
All files in folder: EPA AQS csv file and all of the geoleo data that you may need to run data in their corresponding folders. This is mainly just example data, as there are no APIs in the data to pull directly from the sources. 
Plots
All files in folder: The hourly plots from June 1, 2023 to June 12, 2023 from aeronet, epa aqs, and geoleo data that I have made from this project 
General Notes
Coordinates of the east coast that I was using:
min_lon= -83
max_lon=-69
min_lat=37
max_lat=46
