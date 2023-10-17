# python-api-challenge

Created a random list of citites
Then analyzed the list to plot Latitude vs the below:
    -Temperature
    -Humidity
    -Cloudiness
    -Wind Speed

Linear Regressions were created and analyzed with the findings below:

For Latitude vs. Temperature both the Northern and Southern Hemispheres are strongly correlated at over .75 with the Northern Hemisphere being inversely correlated and the Southern Hemisphere being correlated and increasing in temperature as Latitude increases. For Humidity in the Northern Hemisphere, there is a lot more vaiability with only a rvalue of .09 and a slope of .1 showing a weak correlation. Humidity in the Southern Hemisphere is slightly more correlated with an rvalue of .22 and a stronger slope. Cloudiness is very widely dispersed for both the Northern and Southern Hemispheres and not very highly correlated with rvalues of .17 and .21 respectively. Wind speed is even less correlated for both hemispheres with the Northern Hemisphere having an rvalue of .16 and the Southern Hemisphere at .12. Based on this data, Temperature is strongly correlated to Latitude however all other weather phenomenon analyzed are weakly correlated.

In the second file, those cities were filtered based on temperature and humidity then maps were created showing the locations on the globe and highlighting hotel information as available.