   <p align="center"><img src="images/NES_night.jpg"></p>                                     

# <p align="center">Monthly energy consumption over time by customer type and ZIP Code in Nashville TN.</p>

## Inspiration 
Nashville is experiencing a rapid growth in its population. It is estimated that an average of 100 people move to Nashville per day (Tennessean, April 2019). People are looking for a place to settle with their families that fit their budget. According to these estimates, providing readily available information to visitors on the average energy consumption by ZIP Code per month could alleviate the time spend searching for the right place to live, thus increasing city productivity. 

<p align="center"><img src="images/Nashville pop growth.png" width="400" height="400"></p> 


To address the above problem, I analyzed the Nashville Electric Service (NES) data from 2012 to 2018 to find how average energy consumption patterns have changed over time across different ZIP Codes.


Within the framework of sustainable development, the energy supply system is one of the most crucial subjects. People spend more time searching for the right place to live and one that suits their lifestyle and budget. I embarked on analyzing energy consumption per year and per month to provide the insights of the average energy usage  by residential, commercial, outdoor lighting, and seasonal customers. 


## Data selection
To address the above problem, I analyzed the NES data from 2012 to 2019 to determine how average energy consumption patterns have changed over time across different ZIP Codes.  

The Nashville Electric Service data is publicly available at [Nashville Electric Service](https://data.nashville.gov/Energy-Usage/NES-Monthly-Energy-Consumption-by-Customer-Type-an/vbx7-mn5i). 

 <img src="images/retail sales of lectricity.png"> 

## Data cleaning
The Data wrangling was done before any analysis took place. The ZIP Codes were split from latitude and longitude column. The Customer type dataframes were created, then the annual and monthly electric consumption was analyzed over the years. 

## Visualization
I created a dashboard that hosted different pieces of information. I used matplotlib.pyploy to create different visualizations. The graphs shown on the left represent the average monthly energy consumption per ZIP Code. The chloropleth map on the right shows the ZIP Codes with the highest energy consumption.
<img src="images/Average_energy_consumption_per_zip.png" width="400" height="400"> <img src="images/chloropleth_map_3.png" width="400" height="400">


The top 10 ZIP Codes with the lowest monthly energy consumption for residential customers is shown below.
<img src="images/Lowest 10 energy consuming zip codes.png" width="400" height="400"><img src="images/map-lowest-10 energy consuming zip code.png" width="400" height="400">

The chloropleth maps below shows the energy consumption over time.

<img src="images/Residential energy consumption 2012.png" width="260" height="260"><img src="images/Residential energy consumption in 2015.png" width="260" height="260"><img src="images/Residential energy consumption in 2018.png" width="260" height="260">

I used Tableau to create and interactive visualization [Nashville Electric Service(NES) monthly energy consumption](https://public.tableau.com/profile/bush1897#!/vizhome/EnergyConsumption_15781937576950/Mydashboard?publish=yes) dashboard.
