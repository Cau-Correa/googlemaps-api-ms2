# Milestone Project 2 - Google Maps API

[View the live project here.](https://cau-correa.github.io/googlemaps-api-ms2/)


![Screenshot Responsive](/readme-images/responsive-image.png)
## UX
The aim of this project is to serve as a tool for the user, helping them to find hotels with a simple search by city and country with results showing in the map that for default is centred in Ireland.
Another map of Ireland shows heritage sites of national and tourist interest in Ireland, as an option to the user make their decision where to stay.

### User Stories

#### First time visitor goals:

* As a First Time Visitor, I want to find a hotel in the Republic of Ireland.
* As a First Time Visitor, I want to learn where are located the heritage sites in Ireland. 


#### Returning visitor goals:

* As a Returning Visitor, I want to get details about hotels in different countries to plan my holidays.
* As a Returning Visitor, I want to increase my knowledge about Ireland culture.


#### Frequent user goals:
* As a Frequent User, I want to get information like the rating and website of a hotel to decide the best place to stay.


## Features
This website was planned for mobile first, with a clean and simple design, and heavily relied on google maps javaScript API samples. On the first page, is the main part of this project a map where the user can search for hotels with place autocomplete. The search can be in a specified place within a given country and show details of each hotel. The about section explains the website and guides the user on how to use it. With the second map, the user gets a bird's eye view of Ireland's heritage sites.

## Future features
As future features would be interesting add Geolocation API and Google Photos API.


## Technologies Used
1. [Git](https://git-scm.com/) Was used for version control by utilizing the Gitpod terminal to commit to Git and push it to GitHub. 
2. [GitHub](https://github.com) Used to store the project after it has been pushed from Git.
3. [Boostrap](https://getbootstrap.com/) The Bootstrap library was used throughout the project to assist with the responsiveness and styling of the website.
4. [FontAwesome](https://fontawesome.com/) The project uses Font Awesome icons.
5. [Google Fonts](https://fonts.google.com/) Google fonts were used to homogenize the project. The font imported to the style.css file was 'Oswald'.
6. [Google Maps Platform APIs](https://developers.google.com/maps/documentation) Google maps and places API.


## Design

* ### Colour Scheme
It was used light color in the background to not distract the user neither compete with the map's content.

* ### Typography
The font Oswald was used throughout all pages.

* ### Design choices.
Navbar in the small screen was kept without dropdown menu because it has only 3 items and it doesn't take much space, this way the menu stays visible all the time.

* ### Wireframes.Desktop Wireframe
![wireframe](/readme-images/desktop-wireframe.png)
Tablet Wireframe
![wireframe](/readme-images/tablet-wireframe.png)
Mobile Wireframe
![wireframe](/readme-images/mobile-wireframe.png)


## Languages used

* HTML 5
* CSS 3
* JavaScript


## Testing  

Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.
The Website was tested on Google Chrome, Windows, Linux Opera, and Safari browsers.
The website was viewed on a variety of devices such as iMac, Dell laptop, iPad Air1, Samsung S9, iPhone8, iPhoneX, iphone12 pro & galaxy A30.


### 1 -Testing User Stories from User Experience (UX) Section

#### First Time Visitor Goals
##### * As a First Time Visitor, I want to find a hotel in the Republic of Ireland.
Because the map is already loaded in Ireland the user just needs to type a city and find a hotel to stay.

![Screenshot UX search in Ireland](/readme-images/user-story-first-time-visitor-1.png)

##### * As a First Time Visitor, I want to learn where are located the heritage sites in Ireland.
The map in the Heritage page gives to the user a bird's eye view of all heritage sites in the Republic of Ireland.

![Screenshot UX bird's eye view heritage sites](/readme-images/user-story-first-time-visitor-2.png) 

#### Returning Visitor Goals
##### * As a Returning Visitor, I want to get details about hotels in different countries to plan my holidays.
The user can search in any city and country of their choice.

![Screenshot UX bird's eye view heritage sites](/readme-images/user-story-returning-visitor-1.png) 

##### *As a Returning Visitor, I want to increase my knowledge about Ireland culture.
In the heritage map, the user can find where is a specific site of tourist interest.

![Screenshot UX bird's eye view heritage sites](/readme-images/user-story-returning-visitor-2.png) 

#### Frequent User Goals
##### * As a Frequent User, I want to get information like the rating and website of a hotel to decide the best place to stay.
They can click on a specific mark on the map and see useful information about that hotel.

![Screenshot UX bird's eye view heritage sites](/readme-images/user-story-frequent-user-1.png) 


### 2- Code Validation 

To ensure there were no syntax errors in the project, the [W3C Markup Validator](https://validator.w3.org/), [W3C CSS Validator Services](https://jigsaw.w3.org/css-validator/) and [Jshint](https://jshint.com/) were used to validate every page of the project.

* [W3C Markup Validator](https://validator.w3.org/)

All HTML pages of this project went through *W3C Markup validation service*, With no errors to show.

* [W3C CSS Validator Services](https://jigsaw.w3.org/css-validator/) 

The CSS of this project went through *W3C CSS Validation Service*, W3C CSS Validator results for TextArea (CSS level 3 + SVG) With no error found.

* [Jshint](https://jshint.com/)

All JavaScript went through JSHint with no errors found.

* Lighthouse Google Chrome Tools 

Desktop device:
![lighthouse report desktop](/readme-images/lighthouse-desktop-report.png)

Mobile device:
![lighthouse report mobile](/readme-images/lighthouse-mobile-report.png)


### 3- Manual Testing 

I proceeded with manual testing of every and each button, link and text box in 
the website in all pages. No problems detected with the website working as supposed to.

* The hotel Icon on the top left of the page redirect the user to the Home page been clicked from any of the 3 pages.
* The menu bar with Home, About and Heritage are working as expected opening their respective pages.
* The message/link in the 404 page, when clicked redirects the user to the Home page.
* The map's functionality was also was tested. Results can be found in the UX user stories.
 

### 4- Testing Site Responsiveness 

This project responsiveness was tested with the site like https://responsivedesignchecker.com/ with 
visualisation of this project in many devices sizes and brands, like desktops, notebooks, tablets and mobiles. 
This project seams to have no problems in any size or brand keeping with a consistent 
responsiveness in all of them. Down below I will add screenshot of some of the devices tested.

Device - 24 inches desktop

![responsiveness 24 inches desktop](/readme-images/24-inch-desktop.png)

Device - 19 inches desktop

![responsiveness 19 inches desktop](/readme-images/19-inch-desktop.png)

Device - 13 inches notebook

![responsiveness 13 inches notebook](/readme-images/13-inch-notebook.png)

Device - Apple Ipad mini

![responsiveness apple ipad mini](/readme-images/apple-ipad-mini.png)

Device - Amazon Kindle Fire 

![responsiveness amazon kindle fire](/readme-images/amazon-kindle-fire.png)

Device - Samsung Galay Tab 10

![responsiveness samsung galaxy tab 10](/readme-images/samsung-galaxy-tab-10.png)

Device - Apple Iphone 6s/7s plus

![responsiveness apple iphone 6s/7s plus](/readme-images/apple-iphone-6s-7s-plus.png)


### 5- Bugs Documentation - Documentation of any bugs encountered and their resolution steps 

* Map not loading when Home page is accessed by the Icon and Home button on top of the page.

When the home button and icon on top of the page was clicked suppose to open a fully working map 
in the Home page, the map's functionality was broken, with following error appearing on the console: 
"Google Maps JavaScript API error: RefererNotAllowedMapError https://developers.google.com/maps/documentation/javascript/error-messages#referer-not-allowed-map-error 
Your site URL to be authorized: https://caucorrea.github.io/googlemaps-api-ms2/index.html".
I accessed the Google Cloud Platform and added the https://caucorrea.github.io/googlemaps-api-ms2/index.html to the API restricted access. No alteration on the code was needed.

Screenshot of broken Map's functionality
![screenshot map not loading](/readme-images/map-not-loading-index.png)


* 404 error page not loading.

On the making a 404 page, first added the html page (not-found-page.html) then I created the .htaccess file with one line code in it: 
(ErrorDocument 404/not-found-page.html). To test if it was loading correctly, I tried to access a nonexistent 
page adding random characters at the end of the URL. Instead of the costume 404 page a default error page was loading. 
In the Slack community I found a pin post about creating the 404 error page, using a 404.md file with one line code: in it
(permalink: /404.html). Then I deleted the .htaccess file and renamed the html page to 404.html. 
What seams to be the right way to create a 404 error page.

Screenshot of default page loading instead of customized 404 page
![screenshot default 404 page](/readme-images/default-404.png)

* 404 error page not redirecting to Home page.

When I access a nonexistent page adding random characters at the end of the URL of the site a 404 error page loads with a message: 
This page isn't available. Sorry about that. / Click here to go back to the Home Page / 404 error. 
when I clicked in the link it wasn't been redirecting to the Home page as it supposed to, a default 404 error 
message was showing up, I tried to search for a solution on Slack Community what was unsuccessful, then I went for tutor assistance, 
the tutor Stephen could identify that the problem was in the link. In the href attribute I added index.html. Instead of redirecting 
to the Home page it was creating a broken link, once I replaced index.html with the site's absolute URL the problem was solved.


### 6- Expected Bugs Documentations

* Bug with map functionality.

The hotel icon and button on top of the page should redirect the user to the Home page, that feature wasn't working properly for lack of 
adding index.html in the google maps API restriction access. The problem was fixed with addition of index.html to the autorized 
URL in google maps credentials. Now home button and Icon are working as expected, loading the homepage, when they are clicked on. 
No alteration on the code was needed.

Map is open with index.html
![screenshot testing map functionality](/readme-images/map-open-with-indexhtml.png)


* Testing if custom 404 page is loading.

After making the error page with the file 404.md the site loads a customized 404 error page in case the user try to access a non-existent
 page. If that happens the 404 page will load with a message:
 
 - This page isn't available. Sorry about that. / Click here to go back to the Home Page / 404 error. - 
 
 keeping the user in the site and offering explanation with easy way back to the Home page.


 404 error page loaded if tried access non-existent page
![404 error page loaded](/readme-images/error-page-loaded.png)


## Deployment

### Git Commands
After writing the code on Gitpod, I used the Git Commands:
* git add and file or directory name adds files to the staging area for Git.
* git commit -m "message", record the changes made to the files to a local repository.
* git push, sends local commits to the remote repository on GitHub. 

### GitHub Pages
* The deployment was deployed to the GitHub pages. From my GitHub web page, I open the repository I want to deploy, in this case, “Username-projectname”. Then at the top right of the page click on the 'Settings' link, and scroll down to the GitHub Pages section, I selected the master branch as the source, click on save, and I was provided with the following message: Your site is published at (project URL)/

### Forking the GitHub Repository
* Once you locate the repository you want to fork, at the top right of the page below the right items in the navigation bar the fork button can be located.Now you should have a copy of the original repository in your GitHub account.

### Making a Local Clone
* important not forget GitHub repositoryYou find step by step how to clone a repository from GitHub to your computer on [GitHub Docs](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository) Cloning a repository from GitHub.


## Credits

* ### CodeThis project used Google Maps and Google Place API samples customized for the website needs.
* ### ContentAll content was written by the developer.
* ### MediaGeoJson Map [data.gov.ie](https://data.gov.ie/dataset/heritage-osi-national-250k-map-of-ireland2/resource/6f42c61c-bfaa-4047-a81a-7886b11d740f?view_id=40072f09-14fe-4b97-ba1a-10019d885f8c)

 ### Acknowledgements
* My Mentor Reuben Ferrante for his help and feedback during very early calls.
* Tutor support at Code Institute for their support.