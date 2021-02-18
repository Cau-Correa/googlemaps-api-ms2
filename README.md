# Milestone Project 2 - Google Maps API

[View the live project here.](https://cau-correa.github.io/googlemaps-api-ms2/)


![Screenshot Responsive](/readme-images/responsive-image.png)
## UX
The aim of this project is to serve as a tool for the user, helping them to find hotels with a simple search by city and country with results showing in the map that for default is centered in Ireland.
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

- Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.
- The Website was tested on Google Chrome, Windows, Linux Opera, and Safari browsers.
- The website was viewed on a variety of devices such as iMac, Dell laptop, iPad Air1, Samsung S9, iPhone8, iPhoneX, iphone12 pro & galaxy A30.


### Testing User Stories from User Experience (UX) Section

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


#### Frequent User Goals
##### * As a Frequent User, I want to get information like the rating and website of a hotel to decide the best place to stay.
They can click on a specific mark on the map and see useful information about that hotel.
![Screenshot UX bird's eye view heritage sites](/readme-images/user-story-frequent-user-1.png) 


## Validation

To ensure there were no syntax errors in the project, the [W3C Markup Validator](https://validator.w3.org/), [W3C CSS Validator Services](https://jigsaw.w3.org/css-validator/) and [Jshint](https://jshint.com/) were used to validate every page of the project.

* W3C HTML Validator
All HTML pages of this project went through *W3C Markup validation service*, With no errors to show.

* W3C CSS Validator
The CSS of this project went through *W3C CSS Validation Service*, With no error found.

* Jshint
No errors found.

* Lighthouse Google Chrome Tools 

Desktop device:
![lighthouse report desktop](/readme-images/lighthouse-desktop-report.png)

Mobile device:
![lighthouse report mobile](/readme-images/lighthouse-mobile-report.png)


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