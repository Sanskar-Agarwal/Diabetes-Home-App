<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
  <div align="center">

  <img src="public/images/logo-full.png" alt="logo" width="500" height="auto" />
  <h1>About</h1>
  </div>
  <p>
  Diabetes@Home is a web application that has been developed as an interactive application between a doctor and their patients to help them manage diabetes from the convenience of their own home.

  The project has been developed using Javascript, HTML and CSS. MongoDB has been used to store all patient information and the application had been deployed on Heroku(Since Heroku is a paid service and the free subscription was only valid for the subject, the link is no longer available(We are still on a student budget!)).
  Further information on the tech-stack and features can be found below.

    
   <img src="public/images/readme/homepage.jpg" alt="home-page" />
   <img width="1119" alt="image" src="https://github.com/Sanskar-Agarwal/Diabetes-Home-App/assets/86827884/5fe7b3d7-e42d-47f4-92f5-28e51ce519e3"> 
   <img width="1116" alt="image" src="https://github.com/Sanskar-Agarwal/Diabetes-Home-App/assets/86827884/ce369f7f-94b2-488c-8a29-7a7813712435">
   <img width="1118" alt="image" src="https://github.com/Sanskar-Agarwal/Diabetes-Home-App/assets/86827884/44da314a-311e-4ff3-a49a-b618a6f2ad07">

  </p>
   

<br />


<!-- TechStack -->
### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://nodejs.org/en/">Node.js</a></li>
    <li><a href="https://handlebarsjs.com/">Handlebars </a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express.js</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
  </ul>
</details>

<details>
<summary>DevOps</summary>
  <ul>
    <li><a href="https://www.passportjs.org/">Passport.js</a></li>
  </ul>
</details>

<!-- Features -->
### :dart: Features

- Feature 1
  Record Patient Data - Can be done by either client or Doctor
- Feature 2
  Manage Patient Data - Parameters such as allowed insulin range set by Doctor only
- Feature 3
  Take notes - Doctor can make notes on different patients that are not visible to patients
- Feature 4
  Interactive chat - Patient and Doctor can message each other

<!-- Color Reference -->
### :art: Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary Color | rgba(1, 58, 99, 1) |
| Secondary Color | rgba(185, 218, 235, 1) |
| Accent Color | rgba(5, 85, 142, 1) |


<!-- Env Variables -->
### :key: Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`MONGO_URL="mongodb+srv://username:password@cluster0.gv1sn.mongodb.net/test"`

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses npm as package manager

```bash
 npm install --package here
```

<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/Sanskar-Agarwal/Diabetes-Home-App/
```

Go to the project directory

```bash
  cd Diabetes-Home-App
```

Install dependencies

```bash
  npm install luxon
  npm install express-validator
  npm install express
  npm install passport
  npm install bcrypt
```

Start the server

```bash
  node app.js
  or
  nodemon app.js
```

<!-- Acknowledgments -->
## :gem: Acknowledgements

This project has been developed for INFO30005 Web IT Project by Sanskar, Kian and Sean.


