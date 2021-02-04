**Edit**: Choropleth maps are not available in the preview of the Jupyter Notebook. If you wish to use the interactive map, use Anaconda to open the notebook.

# Covid-visualization
Visualizing the Coronavirus Pandemic with Choropleth Maps

I am a huge advocate for data visualizations because I believe that it is the most effective method to illustrate and explain complex information, especially numerical data, in a simple and digestible manner. Also when performed properly, visualizing data can reduce or help mitigate bias in data interpretation.

I had heard about the Choropleth Maps and wanted to use it for sometime now and what better to visualize sitting at home due to covid virus than the covid virus itself.

# Context
From World Health Organization - On 31 December 2019, WHO was alerted to several cases of pneumonia in Wuhan City, Hubei Province of China. The virus did not match any other known virus. This raised concern because when a virus is new, we do not know how it affects people.

So daily level information on the affected people can give some interesting insights when it is made available to the broader data science community.

Johns Hopkins University has made an excellent dashboard using the affected cases data. Data is extracted from the google sheets associated and made available here.

Dataset and the information here is taken from [kaggle](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset)

# Column Description

 covid_19_data.csv

    Sno - Serial number
    ObservationDate - Date of the observation in MM/DD/YYYY
    Province/State - Province or state of the observation (Could be empty when missing)
    Country/Region - Country of observation
    Last Update - Time in UTC at which the row is updated for the given province or country. (Not standardised and so please clean before using it)
    Confirmed - Cumulative number of confirmed cases till that date
    Deaths - Cumulative number of of deaths till that date
    Recovered - Cumulative number of recovered cases till that date
    
# Choropleth Maps

A choropleth map is a type of thematic map where areas or regions are shaded in proportion to a given data variable.

**Static choropleth maps** are most useful when you want to compare a desired variable by region. For example, if you wanted to compare the crime rate of each state in the US at a given moment, you could visualize it with a static choropleth.

An **animated or dynamic choropleth map** is similar to a static choropleth map, except that you can compare a variable by region, over time. This adds a third dimension of information and is what makes these visualizations so interesting and powerful.    


## Covid Tracking website
 If you want to track live updates of the pandemic, make sure you check out [Covid-Tracker](https://covid-tracked.web.app/). 
 A website created by me using React.js, Chart.js and react-leaflet.
 The repository for the same can be found [here](https://github.com/kkd1215/Covid-Tracker)
