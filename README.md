## Overview

_**Plur-Ly World** A world where a user can sign in search the upcoming festivals, artists and genres. User is capable of being able to post about their favorite artists with images,videos or articles_


<br>

## MVP


The **Plur-Ly World** will have a complete full-stack application with full CRUD using the React front-end. It will have a full RESTfull backend with four mutable tables seeded into the database. The front-end will have six seperate screens with five of the screens under the containers file where state will be stored. Users while be able to create an account and log in while being authenticated through the app. While being loggined in the user will be able to post and edit their content using CRUD. The app will be responsive with desktop, tablet and mobile verisions using flexbox and grid styling. 

<br>

### Goals

- REStful Backend
- Artists, Genres & Users Tables
- Containers File To Store Data
- Routes, Controllers & Models For Tables
- Authententication For Users
- Full CRUD 
- Two Media Queries 
- Deployment Through Surge & Heroku 

<br>

### Libraries and Dependencies

> Use this section to list all supporting libraries and dependencies, and their role in the project. Below is an example - this needs to be replaced!

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | Front-End Framework|
|   React Router Dom  | Routing On Front-End|
| Bulma| Styling |
|    Rails      | Back-End Framework|
|  Axios  | API Interaction |
| CORS | Cross-Origin Resource Sharing |
| JWT | Token Based Authentication |
| Bcrypt | Password Security|
| Faker | Seeding Database|

<br>

### Client (Front End)

#### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views. No hand-drawn wireframes. Use a tool like wireframe.cc, Whimsical or AdobeXD

[Desktop Version](https://whimsical.com/plur-ly-world-desktop-St9CBgoPthybA5JKpUgvfd@7YNFXnKbYop7bmhecH6aC)



[Mobile version](https://whimsical.com/plur-ly-world-mobile-P21FxFzRkwpqbrTCGBaKYx@2Ux7TurymNBdbewqeTnN)



-Tablet Views 
<br>
  *Horizontal will have the desktop version
  <br>
  *Vertical will have the mobile version
  <br>
#### Component Tree



[Component Tree](https://whimsical.com/plur-ly-world-components-Y1UHPJRXtZruDvHxb3C8m1@2Ux7TurymNFea92Zs23m)

#### Component Architecture



``` structure

src
|__ assets/
      |__ fonts
      |__ images
|__ containers/
      |__ Container.jsx
|__ components/
      |__ Header.jsx
      |__ Footer.jsx
      |__ EditPost.jsx  
      |__ CreatePost.jsx
      |__ Artists.jsx
      |__ Genres.jsx
      |__ FestivalDetail.jsx
|__ services/
      |__ apiConfig.js
      |__ auth.js
      |__ artists.js
      |__ genres.js

```

#### Time Estimates



| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Repo Setup & Installs   |    H     |     2 hrs      |     TBA     |   TBA    |
| Schema Creation W/Seed Files |    H     |     3 hrs      |     TBA    |     TBA    |
| Models & Routes | H | 3 hrs | TBA | TBA |
| Controllers | H | 3 hrs | TBA | TBA |
| CRUD Testing| H | 3 hrs | TBA | TBA |
| REACT Setup | H | 3 hrs | TBA | TBA |
| Service Files | H | 3 hrs | TBA | TBA |
| Container Files | H | 3 hrs | TBA| TBA |
| User Testing | H | 3 hrs | TBA | TBA |
| Authentication  | H | 3 hrs | TBA | TBA |
|Layout | H | 3 hrs| TBA| TBA |
|Deploy Heroku | H | 2 hrs| TBA | TBA |
| Deploy Surge | H | 2 hrs | TBA | :TBA |
| Functionality  | H | 3 hrs | TBA | TBA |
| CSS Screens | M | 3 hrs | TBA | TBA |
| CSS Components| M | 3 hrs | TBA | TBA |
| Media Queries | M | 3 hrs | TBA | TBA |
| TOTAL               |          |   43 hrs      |     TBA    |     TBA     |


<br>

### Server (Back End)

#### ERD Model

![Screen Shot 2021-08-25 at 2 34 30 PM](https://user-images.githubusercontent.com/86305867/130860772-0fe54efb-9ef3-4617-a4c4-bf80a4f93761.png)





<br>

***

## Post-MVP

- Comments
- Favorites 
- User Feed

***

## Code Showcase

TBA

## Code Issues & Resolutions

TBA
