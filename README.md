<h1 align="center">
   <img alt="Proffy" src=".github/logo.svg" height="100px" />
    <br>Next Level Week <br/>
    <img alt="Next" src=".github/next.svg" height="100px" />
    <br>
    Node.js | ReactJS | React Native
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/civilenginner/Proffy?style=flat-square">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/civilenginner/Proffy?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/license/civilenginner/Proffy?style=flat-square"> 
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square"><br/>
 <a href="https://insomnia.rest/run/?label=Proffy&uri=https%3A%2F%2Fgithub.com%2Fcivilenginner%2Fnew-test%2Fblob%2Fmaster%2F.github%2FInsomnia_proffy.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>
<p align="center">
  <a href="#bookmark-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#construction_worker-structure">Project Structure</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technology">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <img alt="design project" width="650px" src="./.github/design.png" />
<p>

## :bookmark: About

The **Proffy** is a Web and Mobile application designed to help connect students and teachers. Soon, this application offers teachers the possibility to register classes, being able to add information like the discipline, the cost and time and students the possibility to search for registered classes.
  
This project was designed with the **6 de August**, in Brazil where is the **National Day of Education Professionals**.
  
This application was made during the Next **Level Week #2**, project made by [Rocketseat](https://rocketseat.com.br/).

## :construction_worker: Structure


**Structure Mobile**

[![Proffy Structure Mobile ](https://user-images.githubusercontent.com/49798275/97535450-6d0a9480-199a-11eb-8c2b-27a520ab946a.gif)](https://www.figma.com/file/Img69KhULXdSJ0Mxq0CqhE/Proffy-Mobile-Structure?node-id=0%3A1)

**Structure Web**

[![Proffy Structure Web ](https://user-images.githubusercontent.com/49798275/97535557-93c8cb00-199a-11eb-9178-845420b42d5e.gif)](https://www.figma.com/file/y9lz2EajK3IPn19Zy1ZxTZ/Proffy-Web-Structure?node-id=0%3A1)
## :rocket: Technology

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Express](https://expressjs.com/)
-  [axios](https://github.com/axios/axios)

## :boom: How to run

- ### **Prerequisites**

  - It's **necessary** to have **[Node.js](https://nodejs.org/en/)** installed on the computer
  - It's  **necessary** to have  **[Git](https://git-scm.com/)** installed and configured on the computer
  - It's also **need** have a package manager be the **[NPM](https://www.npmjs.com/)** or **[Yarn](https://yarnpkg.com/)**.
  - Lastly, It's **necessary** to have **[Expo](https://expo.io/)** globally installed on the machine

1. Clone the repository:

```sh
  $ git clone https://github.com/civilenginner/proffy.git
```

2. Running the Application:

```sh
  # API
  $ cd server
  # Installing the project dependencies.
  $ yarn # ou npm install
  # Setting up the database and creating the tables.
  $ yarn knex:migrate # ou npm run knex:migrate

  # Start the API
  $ yarn start # or npm start

  # Web application
  $ cd web
  # Installing the project dependencies.
  $ yarn # ou npm install
  # Launch the web application
  $ yarn start # ou npm start

  # Mobile application
  $ cd mobile
  # Installing the project dependencies.
  $ yarn # or npm install
  # Launch the mobile application
  $ yarn start # ou npm start
```


## :memo: License

This project is under the MIT license. See the archive [LICENSE](LICENSE.md) for more details.

---
<sup>Project developed with the tutorship of [Diego Fernandes](https://github.com/diego3g), by [Rocketseat](rocketseat.com.br).</sup>
