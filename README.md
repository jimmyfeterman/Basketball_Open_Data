# Basketball_Open_Data
Using OpenNYC and MapBox API to map basketball courts in NYC: 


  * The NYC basketball courts directory can be found here: https://data.cityofnewyork.us/Recreation/Directory-of-Basketball-Courts/b937-zdky
    * I use XML version of the file, parse it and put it into a pandas dataframe   
  *  The geographical coordinates of each court are used to do a reverse geocode search via the MapBox API: https://www.mapbox.com/api-documentation/?language=Python#geocoding
