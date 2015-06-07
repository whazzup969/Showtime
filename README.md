# Showtime
Geo Location based movie times finder

## Project Description
A single page webpage that leverages the geolocation functionality in the browser as well as Google maps api and Fandango's movie rss feed to enable a user to retrieve a list of local theaters and what movies they are currently showing.

### Implementation Information 
There are three files needed for implementation:
* _index.html_ - the main file for the application.
* _xml2json.js_ - a utility script that is used to create JSON objects from xml strings
* _ba-simple-proxy.php_ - a php file that is used to proxy the fandango rss request.
 
Development was done against the Google Chrome browser and was testing on Chrome, and Firefox both both desktop and mobile (Android) devices.

### Expected Use Case
* Navigate to html page in browser 
* The UI should load and after the geoLocation in determined and the matching zipcode is determined the text input will be prepopulated with the user's current zipcode. 
* The user can then click search to use that zipcode or type into the input file a different zipcode to look up.
* The matching theaters should be displayed below the input form. If there are no matching theaters a message is displayed. _Ex. 28621 zip code_
