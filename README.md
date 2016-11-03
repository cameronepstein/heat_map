# HEATMAP

Version: ```1.0```<br>
Configuration: ```npm install```<br>
Local Server: ```npm start```<br>

A heatmap generator which takes an input area from the google maps api and generates clusters of random hotspots.

These maps could be used in data driven environments to coordinate research based on a users specified conditions.

![Alt text](http://3.bp.blogspot.com/-5ecRBELlkaU/TxDJrdSLt2I/AAAAAAAAM_Q/bxEGDza7WWw/s523/mapsmania.gif)

## User Sories

As a user,<br>
So that I can define a rectangular search area for my heat map,<br>
I would like an input for two sets of (latitude and longitude) coordinates.<br>

As a user,<br>
So that I can define the amount of data ‘hotspots’ on my heat map,<br>
I would like an input for a number of points to be randomly generated at different positions within the search coordinates.<br>

As a developer,<br>
So that there are examples of higher intensity sections between the defined coordinates,<br>
I would like the application to generate between 1 and 10 “clusters”<br>

As a user,<br>
So that I can view and update my heat map without issues,<br>
I would like this application to be lightweight and represented using the google maps and heat map.js API’s.<br>
