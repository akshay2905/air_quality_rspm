# Data Visualization - Air Quality 
##### With respect to Respirable Suspended Particulate Matter(RSPM) in air quality stations under National Air Quality Monitoring Programme (NAMP)in the year 2008


## About
Data Visualisation of Air Quality of the clusters of station with respect of RSPM in air quality stations under NAMP for year 2008. The map is layered with clusters of air quality stations. The areas are categorised in three section - Industrial , Residential and other areas and Sensitive Areas. 

####Each area can be identified with a symbol - 

   Industrial Icon - Industrial Area.  
   Tree Icon - Sensitive Area.  
   Home Icon - Residential and Other Area.  

#### Markers colors represent the air quality in the area -

   Black - Critical Level of RSPM  
   Red - High Level of RSPM  
   Orange - Moderate Level of RSPM  
   Blue - Low level of RSPM

#### The markers have an onclick Feature which genrates a popup containing information of the properties. 

   The list of properites are -  
   Name of Location  
   Numbers of monitoring days (n)  
   RSPM - Annual average (g/m3)  
   Percentage - exceedence(24 hourly)  
   Area Type  
   Air Quality  
   
### Data Source - www.datagov.in

#### Work that had to be done -   
   Grabed the Dataset in CSV format.  
   Loaded the CSV file in a dataframe in Pandas(Python).  
   Did initial analysis.  
   Grabed Latitude and Longitude of the locations form Google Maps Geocoding API. 
   Added the grabed data to the Dataframe.  
   Cleaned the data by removing some Indentified characters.  
   Converted the data to Json format and then converted to geoJSON form.  
   Wrote the data in geoJSON format to a file.  
   Wrote the javascript code for the map.  
   Voila!!
   
   




