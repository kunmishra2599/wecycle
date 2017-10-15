# WeCycle

Created: 13:40 14/10/17 - 12:00 15/10/17
Built by: Kunal Mishra and Shiv Alagar for iNTUition 2017

This is a tool to help make cycling easier and more fun for you, by helping you find the easiest route with the least inclination and the least gear changes. The tool is hosted [here](http://kunmishra2599.github.io/wecycle).

This tool is written with HTML, CSS and Vanilla Javascript. It uses the Google Maps API, the Google Elevation API and the Geocoder API. 
We take in inputs in the form of pincode locations, which are then converted to Latitude and Longitude values. 

A path is formed between the two points, and the angle of inclination is calculated using the altitude difference between consecutive points and the distance between each of the points. This is used as a threshold value to determine the force needed to cycle (uphill or downhill) and is then correlated with the group of gears needed to achieve that force.

Our data is available as a JSON, which is uploaded on the repository.
