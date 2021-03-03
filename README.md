## User Experience Design

This is the completed User experience design assignment for the class Agile Software Development at NYU CAS. The instructions can be viewed in the ![instructions-app-map-wireframe.md](/instructions-app-map-wireframe.md)
Below are the app map and wireframes designed for the software project. It is advised to view this README file in the newly opened tab.


### App map

![App Map](/ux-design/CovidTravelAgent-app-map.png)

### Wireframes

1\. **Home** <br><br>
![1.A. Home page - basic version ](/ux-design/CovidTravelAgent-Home-basic.png )&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Home page - basic version with opened menu](/ux-design/CovidTravelAgent-Home-basic-with-menu-opened.png) <br>
1.A. Home page - basic version  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp; 1.B. Home page - basic version with opened menu <br><br>
1.A. **Home page - basic version** <br>
Description: This page is the version of the Home page with 'basic' input options and functionality and a closed hamburger menu. The page allows the user to enter citizenship, location and desired airport information and calculate the best travel locations personalised for them. Destinations will be ranked based on a cumulative points based system and the user can view and sort results based on the inputs and various COVID related data points.  <br>
Optionally, the page allows to select additional inputs - once the user checks the 'advanced' box, additional input options and functionality will be displayed. Once the user checks the 'Calculate' button, he/she will be redirected to the confirmation page. <br><br>
1.B. **Home page - basic version with opened menu** <br> 
Description. This page is the version of the Home page page the 'basic' input options and functionality (as in 1.A) and contents of the hamburger menu displayed. The hamburger menu allows the user to navigate to the primary pages of the app.<br><br>
![1.C. Home page with 'advanced' box checked ](/ux-design/CovidTravelAgent-Home-with-advanced-checkbox-checked.png)  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![1.D. Home page with 'advanced', 'receive updates' boxes checked](/ux-design/CovidTravelAgent-Home-with-advanced-and-receive-updates-checkboxes-checked.png)<br> <br>
1.C. Home page - advanced version &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.D. Home page with 'advanced', 'receive updates' boxes checked <br> <br> 
1.C. **Home page with 'advanced' box checked** <br> 
Description. This page is the version of the 'Home page ' page with the advanced box checked and additional inputs and functionality made available to the user; the hamburger menu is closed. Advanced inputs include desired continent for travel, reason for travel, optional name and email address. If the user provides their email address, they can check the 'receive updates' box and additionally opt to receive rolling updates as new destinations become available to the user, which will be sent via email. <br><br>
1.D. **Home page with 'advanced', 'receive updates' boxes checked** <br> 
Description. This page is the version of the 'Home page ' page with the 'advanced' and 'receive updates' boxes checked and additional inputs and functionality made available to the user; the hamburger menu is closed. As described in 1.C, when the user checks the 'receive updates' box, he/she will receive emails with the rolling updates on new travel destinations as they become available.<br><br>
1.1. **Confirmation** <br> 
![1.1.A. Confirmation - closed menu](/ux-design/CovidTravelAgent-Confirmation.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![1.1.B. Confirmation - opened menu](/ux-design/CovidTravelAgent-Confirmation-with-menu-opened.png) <br>
1.1.A. Confirmation - closed menu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;  1.1.B. Confirmation - opened menu <br><br>
1.1.A. **Confirmation - closed menu** <br>
Description: This page is a version of the Confirmation page with closed hamburger menu. The page allows the user to validate input entered in the home page. Particularly, the page allows the users to view the entered data (with suggested spelling edits) and the map focused on the user entered location. Confirmation of the location is required to resolve any ambiguity related to city names. For example, there can be several cities named Springfield across the country and even states - allowing the user to reconfirm location on the map will minimise user input mistakes. The page also allows the users to return to the home page with the calculations and edit inputs.<br><br>
1.1.B. **Confirmation - opened menu** <br> 
Description: This page is the version of the 'Comfirmation' page with the contents of the hamburger menu displayed. The hamburger menu allows the user to navigate to the primary pages.<br><br> 
1.1.1. **View top locations** <br> 
![1.1.1.A. View top locations - closed menu](/ux-design/CovidTravelAgent-View-top-locations.png) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![1.1.1.A. View top locations - opened menu](/ux-design/CovidTravelAgent-View-top-locations-with-menu-opened.png) <br>
1.1.1.A. View top locations - closed menu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 1.1.1.B. View top locations - opened menu <br><br>
1.1.1.A. **View top locations - closed menu** <br> 
Description: The view top locations page allows the user to view the best personalized locations to travel based on a synthesis of various COVID related data points; the locations can be sorted based on scores. The page contains images of each location and links to view the COVID related dataset for each location. <br><br>
1.1.1.B. **View top locations - opened menu** <br> 
Description: This page is the version of the 'View Top Locations' page with the contents of the hamburger menu displayed.<br><br>
1.1.1.1. **COVID details for location** <br> 
![1.1.1.1.A. COVID details for location closed menu](/ux-design/CovidTravelAgent-COVID-info.png) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![1.1.1.1.A. COVID details for location - opened menu](/ux-design/CovidTravelAgent-COVID-info-with-menu-opened.png) <br>
1.1.1.1.A. COVID details for location - closed menu &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.1.1.B. COVID details for location - opened menu <br><br>
1.1.1.1.A. **COVID details for location - closed menu** <br> 
Description: This page can be reached from the page "View Top Locations" once the user selects to view COVID related data for a particular country. This page displays information on the current number of COVID cases, percentage of population vaccinated, mortality risk, quarantine requirements, and gov. stringency index. From this page, the user can navigate to the flights related information, or return to view other top locations. There will be a defined number of 'COVID details' pages standardized for all recommended locations. <br><br> 
1.1.1.1.B. **COVID details for location  - opened menu** <br> 
Description: This page is the version of the 'COVID details for location' page with the contents of the hamburger menu displayed.<br><br> 
1.1.1.1.1. **Flight details for location** <br> 
![1.1.1.1.1.A. Flight details for location - closed menu](/ux-design/CovidTravelAgent-Flight-info.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![1.1.1.1.A. COVID details for location - opened menu](/ux-design/CovidTravelAgent-Flight-info-with-menu-opened.png)<br>
1.1.1.1.1.A. Flight details for location - closed menu  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.1.1.1.B. Flight details for location - opened menu<br><br>
1.1.1.1.1.A. **Flight details for location - closed menu** <br>
Description: This page displays flight information for the user based on their destination and uses travel APIs to show flights from the user's airport of preference to the destination they have selected. From this page the user will be redirected to an external site to view the details for the flights and complete the flight booking. The user can return to the COVID details page or to the page with top locations. There will be a defined number of 'Flight details' pages standardized for all recommended locations. <br><br> 
1.1.1.1.1.B. **Flight details for location - opened menu** <br>
Description: This page is the version of the 'Flight details for locations' page with the contents of the hamburger menu displayed. <br><br> 
1.2. **About us** <br> 
![1.2.A. About us - closed menu ](/ux-design/CovidTravelAgent-About-us.png )&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![1.2.B. About us - opened menu](/ux-design/CovidTravelAgent-About-us-with-opened-menu.png) <br>
1.2.A. About us - closed menu   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.2.B. About us - opened menu <br><br>
1.2.A. **About us - closed menu** <br> 
Description: This page will provide background information on the project and our purpose for creating it. At the top, the page displays a carousel of the images featuring top safe locations to visit. The page also features iframes with our social media pages. Users can navigate to the "Meet the team" page to learn more about the team members. <br><br> 
1.2.B. **About us - opened menu** <br> 
Description: This page is the version of the 'About us' page with the contents of the hamburger menu displayed.<br><br>
1.3. **Meet the team** <br> 
![1.3.A. Meet the team - closed menu](/ux-design/CovidTravelAgent-Meet-the-team.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![1.3.B. Meet the team - opened menu](/ux-design/CovidTravelAgent-Meet-the-team-with-menu-opened.png) <br>
1.3.A. Meet the team - closed menu  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.3.B. Meet the team - opened menu <br><br>
1.3.A. **Meet the team - closed menu** <br> 
Description: This page will provide individual background details of each team member and display the picture of each team member. <br><br> 
1.3.B. **Meet the team - opened menu** <br> 
Description: This page is the version of the 'Meet the team' page with the contents of the hamburger menu displayed. 
<br><br>
1.4. **Safest Locations** <br> 
![ 1.4.A. Safest Locations - closed menu](/ux-design/CovidTravelAgent-Featured-safest-locations.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;!![1.4.B. Safest Locations - opened menu](/ux-design/CovidTravelAgent-Featured-safest-locations-with-menu-opened.png) <br>
1.4.A. Safest Locations - closed menu  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.4.B. Safest Locations - opened menu <br><br>
1.4.A. **Safest Locations - closed menu** <br> 
Description: This page will provide the top 3/5/10 safest locations from our database and will be independent of the user provided information. Any user can navigate to this page from the top navigation (hamburger menu) without filling out the detailed information for calculating travel destinations on the home page. <br><br> 
1.4.B. **Safest Locations - opened menu** <br> 
Description: This page is the version of the 'Safest Locations' page with the contents of the hamburger menu displayed. <br><br>
![ 1.4.C. Safest Locations with details - closed menu](/ux-design/CovidTravelAgent-Featured-safest-locations-with-detailed-info.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![1.4.B. Safest Locations - opened menu](/ux-design/CovidTravelAgent-Featured-safest-locations-with-menu-opened.png) <br>
1.4.C. Safest Locations with details - closed menu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.4.D. Safest Locations with details - opened menu <br><br>
1.4.C. **Safest Locations with details - closed menu** <br> 
Description: This page is the version of the 'Safest Locations' page with more detailed information about each location <br><br> 
1.4.D. **Safest Locations with details - opened menu** <br> 
Description: This page is the version of the 'Safest Locations with details' page with the contents of the hamburger menu displayed. 
<br><br>
1.5. **Travel resources** <br> 
![Travel resources - closed menu](/ux-design/CovidTravelAgent-Travel-resources.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Travel resources - closed menu](/ux-design/CovidTravelAgent-Travel-resources-with-menu-opened.png) <br>
1.5.A. Travel resources - closed menu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.5.B. Travel resources - opened menu <br><br>
1.5.A. **Travel resources - closed menu** <br> 
Description: This page will provide links to the resources about travel restrictions, travel reccommendations and COVID related news via featuring iframes of infographics. <br><br> 
1.5.B. **Travel resources - opened menu** <br> 
Description: This page is the version of the 'Travel resources' page with the contents of the hamburger menu displayed. <br><br>

1.6. **Contact us** <br> 
![Contact us - closed menu](/ux-design/CovidTravelAgent-Contact-us.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Contact us - opened menu](/ux-design/CovidTravelAgent-Contact-us-menu-opened.png)<br>
1.6.A. Contact us - closed menu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.6.B. Contact us - opened menu <br><br>
1.6.A. **Contact us - closed menu** <br> 
Description: This page allows the user to enter their name and email and send a message to us. The user can also navigate to the "About us" and "Meet the team" pages to learn more.
1.6.B. **Contact us - opened menu** <br> 
Description: This page is the version of the 'Contact us' page with the contents of the hamburger menu displayed. <br><br>


[Source File](/ux-design/CovidTravelAgent.drawio)<br>
 [XML File](/ux-design/xml)
 <br>
 [Draw IO Link](https://drive.google.com/file/d/1gBmgFeYnKphelMkwGlDn8Q4sGvdlAAiN/view?usp=sharing)
