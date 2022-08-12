<p align="center">
   <img src="https://user-images.githubusercontent.com/26275918/96444639-e4a82900-120e-11eb-9d8c-69c941c6bdce.png" alt="Happy" width="280"/>
</p>

<div align="center">
  <h4>:rocket: Project made to connect people to orphanages</h4>
</div>

# :pushpin: Table of Contents

* [Technologies](#computer-technologies)
* [Features](#rocket-features)
* [How to Run](#construction_worker-how-to-run)
* [Found a bug? Missing a specific feature?](#bug-issues)

### Web Screenshot
<div>
  <img src="https://user-images.githubusercontent.com/26275918/95751862-78be4180-0c9f-11eb-969d-dde995585c8e.png">
  <img src="https://user-images.githubusercontent.com/26275918/96021176-5bc87080-0e4f-11eb-8364-78d8fd279d87.png">
</div>

### Mobile Screenshot
<div>
   <img src="https://i.ibb.co/RCdcT7M/Screenshot-1603105830.png" width="200">
   <img src="https://i.ibb.co/fr4wsZ1/Screenshot-1603105838.png" width="200">
   <img src="https://i.ibb.co/7k93KN9/Screenshot-1603105847.png" width="200">
   <img src="https://i.ibb.co/CnH3XKk/Screenshot-1603105860.png" width="200">
</div>

# :computer: Technologies
This project was made using the follow technologies:

* [Typescript](https://www.typescriptlang.org/)      
* [React](https://reactjs.org/)      
* [Expo](https://expo.io/)       
* [Express](https://expressjs.com/)      

# :rocket: Features

* App to connect people and orphanates.

# :construction_worker: How to run
```bash
# Clone Repository
$ git clone https://github.com/AdSoNaTuRaL/happy.git
```

### 📦 Run API

```bash
# Go to server folder
$ cd happy/backend

# Install Dependencies
$ yarn
```
> ⚠ Before running the API, you need to rename the ORM configuration file `ormconfig.example.json` to `ormconfig.json` and then set your configurations there. 

> ⚠ Pre-existing configurations are valid. 

> ⚠ In addition, you must to run the migrations using `yarn typeorm migration:run`

```bash
# Run Aplication
$ yarn dev
```
API is accessible at http://localhost:3334/

### 💻 Run Web Project

```bash
# Go to web folder
$ cd happy/web

# Install Dependencies
$ yarn
```
> ⚠ Before running the web project, you need to rename the env file `.env.example` to `.env` and then set your configuration there. You will need the mapbox access token, you can check about it [here](https://docs.mapbox.com/help/getting-started/access-tokens/).

```bash
# Run Aplication
$ yarn start
```
Go to http://localhost:3000/ to see the result.

### 📱 Run Mobile Project
To run the mobile project you need a cellphone with the app of [expo](https://play.google.com/store/apps/details?id=host.exp.exponent) instaled or a emulator Android/IOS.
<br />
After, fork this repository and clone to your machine. Inside of the project's folder run the following commands:

```bash
# Go to mobile folder
$ cd happy/mobile

# Install Dependencies
$ yarn

# Run Aplication
$ yarn start
```
Aferter read the QRCode with the app of [expo](https://play.google.com/store/apps/details?id=host.exp.exponent) or run on emulator.


# :bug: Issues

Feel free to **create a new issue** with a respective title and description on the [Happy](https://github.com/AdSoNaTuRaL/happy/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**!
<>
