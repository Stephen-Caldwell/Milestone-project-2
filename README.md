## What to do, what to do?
This is a simple website that llows users to search for some attractions in the city of their choice. The results are listed and displayed on a map. Users can then search for directions using public transport withing the city tey are going to.

## Site Flow
The site is split into 2 sections at the top is the map and search for the attractions.
### Attraction search
The user will simply enter a city of their choice suggestions for which city will appear as the user is typing.
When the user selects the city pins will populate the map and a list will appear on the right hand side.
The pins on the map are letter and they also appear on the list of attractions.
The user can click a pin on the map or select an attraction from the list, this will open up a small popup window on the map with further information on the attraction.

Please see map.PNG & Results_Map.PNG in https://github.com/Stephen-Caldwell/Milestone-project-2/tree/master/Screenshots

### Transit section
After the user has found the attractions they wish to go to they can scroll down and search for public transport routes to whereever they need to go.
The can also see the different lines of each type of public transport, see the latest alerts, and change the country and language.
Please see Transport Map.PNG, Transport search results.PNG, Transport lines.PNG & Transport alerts.PNG in https://github.com/Stephen-Caldwell/Milestone-project-2/tree/master/Screenshots

### Technologies Used
- HTML
    - I used HTML to build the website
- CSS
    - I used CSS for styling
- Bootstrap
    - I used Bootstrap just for further styling
- Google Fonts
    - I used this for the font families
- JavaScript
    - This was used to link the autocomplete to the map, add interactivity, and to bring up the small info window when the icons were selected on the map.
- Google maps API
    -   I used Google maps API and Google Places API to find and display the results
- Moovit Embedded Widget
    - I used the Moovit API embedded widget to allow users to find public transport routes to whereever they need to go.(https://moovit.com/developers/embedded/)


## Testing
The results below are from manual testing.
1. Autocomplete search bar 
    a. As you type cities relating to letters will apppear in a dropdown menu for you to select.
2. Results table & markers
    a. When you select a city the map will zoom in on that city and lettered markers will appear on the map.
    b. Beside the map the a corressponding list will appear listing the results with the lettered markers beside them.
    c. When you select a result from the table or the marker on the map an info window will come up.
3. Moovit map
    a. Clicking the country name at the top brings up a modal to search for and select a different country on Moovit's system.
    b. Searching for directions returns different routes, times, and modes of transport.
    c. The route will also appear on a map
    d. Map also includes links to download the app to your phone and send the route to your phone.