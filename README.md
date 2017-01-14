#Open Door Events

### Overview
This application provided a visual representation of events on the map. When the user enters a city, the app fetches the events happening in that city from Eventful API and uses the address of the events and pins them on the map using Google maps API. It also fetches the weather forecast for the events from Weather API.

### Demo
[Check to see the demo](https://evening-scrubland-98506.herokuapp.com)

### Technologies used
* Google maps API, Eventful API, Weather API
* JQuery, Javascript, AJAX, promises, JSON
* Firebase database
* Materialize CSS
* HTML, CSS

### Challenges faced

* How to use Eventful, Google maps and Weather APIs?
* How to handle AJAX calls, how to feed the 
* How to get events stored in the database onto full calender?

### Solutions found

* Reading the documentation several times and looking at code samples helped understanding Full Calender.io.
* Finding the link for public holidays from Google Calender API and calling it using Full Calender library function helped solve the the problem.
* Writing API route for the events and seperating scheduled and unschdeduled events and passing them onto Full Calender functions worked.


#### Developed by Bhagya and Chin Long
