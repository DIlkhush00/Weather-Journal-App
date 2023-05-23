# Weather Journal App

Weather Journal App project is developed for Udacity's Front End developer nanodegree.

## Table of Contents
- [Weather Journal App](#weather-journal-app)
- [Table of Contents](#table-of-contents)
- [Description](#description)
- [Technology Used](#technology-used)
- [Setup](#)
    - [Prerequisite](#prerequisite)
    - [Installation](#installation)
- [Preview](#preview)

## Description
This application uses a Web API, OpenWeatherMap API, to get weather information about any place by entering a zip code and presents it in a user-friendly interface.

## Technology Used
This application is built with: 
- HTML
- CSS
- JavaScript

## Setup
Instruction on how to get this app running locally.

### Prerequisite
- Before running this app make sure you have `Node.js` installed on your computer
- Get your personal API key from OpenWeatherMap website

### Installation
1. Clone the repo
```sh
git clone https://github.com/
``` 
2. Run the following Command in terminal to install necessary dependencies
```sh
npm install
```
3. Open `website/app.js` file and replace your personal API key with the value of `APIKey` variable
```javascript
const APIKey = '<your-api-key>'; //Replace <your-api-key> with your personal API key
```
4. Navigate to the path where `server.js` file is and run the following command in terminal
```sh
node server.js
```
5. Open any browser and visit the following url `http://localhost:8080/`
6. There you go :rocket:



## Preview
[Preview](images/preview.png)

