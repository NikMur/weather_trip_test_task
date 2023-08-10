Using React.js (preferably, but you can use Angular or any other framework), implement a Trip app where users can see the weather forecast for their upcoming journeys, following these requirements:
1. Visualization of the page: Main.png.
2. Upon starting the application, user should already have a static list of trips (1 trip is enough). The list should be scrollable.
3. When user selects a trip from the list, a forecast for each day of the trip should be displayed.
4. On the top:
a. There should be a possibility to search for a trip
5. The app should include a button for adding a new trip. When the user clicks on "Add trip," a modal window should appear. Inside the modal, the user should have the ability to:
a. Choose a city from a predefined list (you should have a mock list of
cities that the API supports, with images).
b. Enter the start date of the trip (the start date should be within the next 15 days).
c. Enter the end date of the trip (the end date should be within the next 15 days).
Upon clicking "Done," the trip should be added to the list.
Modal visualization Modal.png
6. On the right side of the page:
a. When user selects a trip, today's weather forecast for that city should be displayed.
b. There should be a countdown real time timer from the current date to the start date of the trip (days - hours - minutes - seconds).
Additionally:
1. Implement next and previous buttons for the list to handle scrolling better
Please, don’t use any UI components libraries, only HTML/CSS

