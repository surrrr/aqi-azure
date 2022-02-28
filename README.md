# aqi-azure

TRACKING AIR QUALITY INDEX USING AZURE MAPS

We are tracking global AQI and visualising it using azure maps web SDK, and we are using pollution data from a third party air quality API(WAQI API).

Azure maps uses longitude and latitude for map coordinates. 
After the page is fully loaded, in the browser, the app requests the user's location. The app can get the user's location only if the user grants permission. If the user doesn't give the browser permission to access their location, the browser uses the default location of DELHI.

We have used colors to represent the AQI, and whether it is safe or not.
if  AQI<=50, green
    AQI<=100, light yellow
    AQI<=150, orangish yellow
    AQI<=200, red
    AQI<=300, Indigo
    AQI>300, burgundy
    
  We retrived air quality data from WAQI API and covert it into GeoJSON format.
  
  
    
