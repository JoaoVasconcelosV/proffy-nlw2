<h1 align="center">
    <img alt="Proffy" src="web/src/assets/images/logo.svg" height="100px" />
    <br>Next Level Week #2<br/>
    Node.js | ReactJS | React Native
</h1>

## :pushpin: About

This is a project done during the week #NLW2 for the [Rocketseat](https://rocketseat.com.br).

Made as a way to honor the National Day of Education Professionals on August 6. **Proffy** is a multiplatform application made to connect students and teachers for private lessons

## :wrench: Technology

- [Node.js](https://nodejs.org)
- [TypeScript](https://www.typescriptlang.org)
- [ReactJs](https://pt-br.reactjs.org)
- [React Native](https://reactnative.dev)
- [Expo](https://expo.io)

## :rocket: Getting start

- **Prerequisite**: It is necessary to have **Git**, **NodeJs**, a package manager (**NPM** or **Yarn**), and **Expo** for mobile application

- **Clone the repository**:

```
    $ git clone https://github.com/JoaoVasconcelosV/proffy-nlw2.git
```

- **Run the application**:

```sh
  # Server
  $ cd server
  $ yarn install # Installing the project dependencies.
  $ yarn knex:migrate # Setting up the database and creating the tables.
  $ yarn start # Starting the Server

  # Application web
  $ cd web 
  $ yarn install # Installing the dependencies.
  $ yarn start # Starting the web application

  # Application mobile
  $ cd mobile  
  $ yarn install # Installing the dependencies.
  $ yarn start # Starting the mobile application
```
