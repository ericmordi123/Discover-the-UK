# Discover The UK APP 

I have created a single page application utilizing the google maps and google places API that enables users to search anywhere in the Uk for the best accommodation, nearby bars/restaurants and tourist attractions within that area. Whether planning a holiday, relocating for work or personal matters or just wanting to explore the country you live in this App makes it simple for you to do so.


# UX DESIGN
The purpose of this App is to give the user the peace of mind of knowing the most important information necessary when traveling, which are the best places to stay and eat as well as all the interesting and fun places to visit in their desired destination. The user can see ratings of each hotel, bar, and restaurant as well as the address and contact details when a green marker is selected.

### User Stories:
Anyone that wants to use this App can do any or all of the following-
A User would be able to see reviews for specific places, for example, a hotel or a restaurant and determine whether or not that place would be worth going to. 
A User would be able to get all details and contact information for any selected location so they can find out more, make a booking or do anything else they wish.
A User can search for clubs and tourist attractions so I can have a realistic idea of what is around me and the things I can do.
A user would be able to use the satellite option or drag the icon on the map to get an actual view of their chosen destination anywhere in the UK so they will know exactly what to expect. 

## FEATURES
Features Used in This Project:
Able to search for any location anywhere in the UK.  

Find the closest hotels/bars/restaurants in that area.

View the ratings of each hotel/bar/restaurant.

View the contact details and address of each hotel/bar/restaurant.

View and select the tourist attractions/points of interest within the specified area.

Added a reset button to refresh the page if you wish to restart your search.

## TECHNOLOGIES
The Technologies I Have Used:
 - [Google Maps API](https://developers.google.com/maps/documentation/javascript/get-api-key) - I have used the Google Maps API for use of their google maps service.
 - [Google Places API](https://developers.google.com/places/web-service/intro) - I have to use the Google Places API for use of their points of interest/hotels/bars to be added to my map.
 - [Bootstrap](https://getbootstrap.com/docs/3.3/getting-started/) - I have used Bootstrap for its grid system, making my application responsive.
 - [Bootswatch](https://bootswatch.com/) - I used Bootswatch in order to keep the theme of my application consistent
 - [Font Awesome](https://fontawesome.com/) - I have used the Bootstrap Font Awesome CDN to make use of their male icon.
 - [jQuery](http://jqueryui.com/) - I have used jQuery for simplicity with my JavaScript.
 - [Google trends](https://trends.google.com/trends/?geo=US) - To get an idea out what people that are traveling in the UK would want to know

## Wireframes
See wireframes in wireframe file.

### Features left to implement 
I was initially going to use D3.js to create traffic graph so that the user could have an idea of the best means of travel and the best times to get around and I found a site called [Numbeo](https://www.numbeo.com/api/doc.jsp) that have an API holds this type of information.
This would have been ideal and a good addition to the app however the company Numbero do not give access to their API without clearing it with them first so I had to contact them and ask for permission and was eventually granted access however as I am only a student I can only use it for a maximum of six months so I chose not to include this as it was not a sustainable addition.

## TESTING
I Tested the functionality of the App on various browsers/devices to ensure Users can successfully use the site and all its features for all intended purposes.

### Tests conducted:

- Checking the functionality of the Google Maps API, making sure everything worked as it should
- Making sure the restriction to only destinations in the UK was working by typing in a city like Los Angles and it not working 
- I also initially included a dropdown bar so you can select a city to search in but I removed it as it really is not necessary because the user can type their city of choice in the search bar anyways so it was taking up unnecessary real estate.
- Reloading page to make sure the pop up that explains the areas you can search works.
- Making sure the code runs without issues using the Google Chrome Inspect Tools. Inside Chromes Dev Tools in order to check the responsiveness for individual phones and screens, for example, an IPad/Samsung.
- Use the console to check the stability of my JavaScript files and all file paths so that there are no errors and it is not broken so there are no issues with deployment. 
- Although the changes are not permanent Chrome Dev Tools allows me to adapt my code and get a preview to see what works and what may need to be changed in order to create the best user experience. This particularly came in handy when having to adjust the map for smaller devices to make sure of the correct alignment was correct. 

- I have used a code Validator for each type of code in my project to make sure my code is clean and there are no issues.
Here is each Validator used:
  - [HTML](https://validator.w3.org/)
  - [CSS](http://www.css-validator.org/)
  - [JavaScript](https://www.beautifyconverter.com/javascript-validator.php)

- I also tested the functionality of the app on a number of browsers/devices (see below) and found no issues
  - Yahoo - laptop, ipad and samsung
  - Chrome - laptop, iPad and Samsung
  - Safari - iPad
  - Internet Explorer - laptop, iPad and Samsung


### User Stories Testing
  - I tested the user's ability to be able to see reviews and info for specific places, for example, a hotel or a restaurant by clicking on the alphabetized markers making sure the full information and contact details are shown in the info window and are easy to see.
  - I also typed in different locations and clicked on different markers to make sure the all hotels/bars restaurants are being shown. 
  - A User would want to search for accommodation so that they can get an understanding of where places are so I can plan my stay. This was tested by making sure I had correctly used the API to fetch the correct places for that location.
  - A User would want to select a specific bar, restaurant or hotel and get the correct contact details and address for that place so that they can give a place a call or visit their website for further info or to arrange a booking. This was tested by again making sure I had used Google's API correctly and it was showing the correct information.

## DEPLOYMENT
Whilst completing this project I constantly committed every bug that was fixed, every update that was made either a change or adding to my code to improve the app, to Github using version control 

I have deployed this application using GitHub Pages which can be found [Here](https://ericmordi123.github.io/Discover-the-UK/).

## CREDIT
I used a number of sights to help me with my work 

* https://www.ranker.com/list/countries-in-united-kingdom/best-world-journeys -- To get info of all UK countries 
* https://trends.google.com/trends/?geo=US -- To get an idea out what people that are traveling in the UK would want to know
* I also used these google map templates as an outline which really helped:  
  * https://developers.google.com/maps/documentation/javascript/examples/places-searchbox  
  * https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch 
* https://developers.google.com/places/supported_types -- To get all supported types in Google places API places 
* I also used [Traversy Media's Youtube Channel on using the google maps API](https://www.youtube.com/watch?v=Zxf1mnP5zcw&t=1347s) Specifically his video showing how to use the Google Maps API to give me a better understanding of how to use google API's.


## ACKNOWLEDGEMENTS
The main goal of this project was to create an App that assists the user with travelling in the UK for whatever reasons and find the best spots, places to stay and things to do and I think I have achieved this and I would like to thank my mentor and slack mentors, friends and study colleagues that helped with ideas and advice
and also the code institute mentors that where always there if I needed anything. Another huge help was all the course and youtube videos that allowed me to go over what I was stuck on.