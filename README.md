# PWA Text Editor
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Technologies Used](#technologies-used)
* [Live Application](#live-application)
* [Usage](#usage)
* [Features](#features)
* [Credits](#credits)
* [License](#license)

## Description

The PWA Text Editor is a web application designed to allow developers to create and manage notes or code snippets, with or without an internet connection. It features data persistence techniques using IndexedDB and is built as a Progressive Web Application (PWA) to ensure reliability and accessibility.

## Installation

To install the PWA Text Editor, follow these steps:

1. Clone the repository to your local machine.
2. Run `npm install` to install all the necessary dependencies.
3. Ensure you have Node.js and npm installed on your machine.
4. Run `npm run start` from the root directory to start the application.

## Technologies Used

This application is powered by Webpack (HTML-Webpack-Plugin, Babel, and CSS Loader), Node.js (v16.19.1), Express.js (v.14.17.1), and JavaScript. Nodemon (v2.0.4) and Concurrently (v5.2.0) were utilized as a devDependencies allowing the server to refresh when edits were made to application, and allowing both the front end and back end to be ran on a single command (npm run start:dev).

![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)

## Live Application

[PWA Text Editor](https://young-brushlands-65623-5b006d80757b.herokuapp.com)

## Usage

After installation, open your browser and navigate to the application's URL. You will be presented with a text editor interface where you can:

- Create and edit notes or code snippets
- Save content locally using IndexedDB
- Access your saved content even when offline

Navigate through the editor to manage your notes and snippets efficiently.

## Features

- Offline functionality for creating and editing text content
- Data persistence using IndexedDB
- Progressive Web Application (PWA) capabilities for reliability and accessibility

## Credits

Developed by Leighton Van Ness with starter code from Columbia EDx Bootcamp

## License

Please refer to the license in the repo.

