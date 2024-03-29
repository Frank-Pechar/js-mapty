# Map and Log Workouts App 
## JavaScript Project
## Description of App Functionality, Features, and Methods

Javascript coding project I completed from Udemy - The Complete Javascript Course 2023: From Zero to Expert by Jonas Schmedtmann. This project was originally designed just for the desktop. I created necessary adaptations for mobile devices. I also made numerous other refinements to the original project. I extensively commented the JavaScript code for educational purposes.

App can be run from: https://frank-pechar-js-mapty.netlify.app/

## App Description

This App logs and maps running and cycling workouts in a list and on a map. A historical record of workout data is kept by storing data to local storage.

## App Functionality 

Log a Workout

- Click on the map where the workout was located
- A form will popup - Enter workout Type: Running or Cycling, Distance, Duration, and Cadence (for running) or Elev Gain (for cycling) - Press Enter
- Workout data will be displayed in a list and the map with a Location Marker
- Clicking on a workout list item will center the map on that marker location
- Closing the App window or browser and then restarting the App in the browser will cause the Workout Data to be re-displayed because the data is stored in the browser local storage area

## Javascript Features and Methods Used

- Base and Sub Classes
- Geolocation API 
- Leaflet Mapping Library API
- Use of Local Storage for persistent workout data
- Event Delegation
- Event listeners of different types
- Form Data
- Private Fields
- Protected methods
- HTML dataset attributes
- Date manipulation
- Responsive design techniques

List of some methods and properties used: 

class, extends, super(), constructor(), navigator.geolocation.getCurrentPosition(), bind(), dataset, Array methods: every, slice, forEach, push, find, ...rest
