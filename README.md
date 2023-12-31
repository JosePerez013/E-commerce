# Module 9 Challenge: README Generator

## Table of Contents

- [Installation](#installation)
- [Description](#description)
- [Usage](#usage)
- [Features](#features)
- [License](#license)

## Description

- A simple and robust E-Commerce back-end API utilizing MySQL as a database.
- With this back-end API, front-end developers can utilize data from a back-end database to use for development.
- This project has furthered my knowledge in back-end database systems and architecture.

## Features

- Utilizes Sequelize to interact with a MySQL database.
- Uses ExpressJS as a web framework, and NodeJS as a server environment.
- GET, POST, PUT, and DELETE HTTP methods for each API endpoint.

## Installation

1. Ensure you have NodeJS installed on your computer. [Click here if you need to install NodeJS.](https://nodejs.org/en)
2. Clone or download the zip of the GitHub repository. Extract and navigate to the repository in your directory.
3. Open your command-line terminal in your repository directory and type `npm i` to download all npm package dependencies needed to run the program.
4. Ensure you have the ecommerce_db schema on your MySQL database schemas. [If unsure on how to setup MySQL schemas, click here.](https://dev.mysql.com/doc/refman/8.0/en/create-database.html)
5. A .env file will be needed to establish environment variables for your database's name, user, and password. DB_NAME, DB_USER, & DB_PW are the required key names to properly initialize your MySQL connection via Sequelize. [If you're unfamiliar with .env files, click here.](https://nodejs.dev/en/learn/how-to-read-environment-variables-from-nodejs/).
6. Once a .env file has been properly set, do `npm start` in your command-line terminal to start the application. IT IS RECOMMENDED TO USE AN APPLICATION LIKE INSOMNIA TO TEST OUT THE BACK-END API. 

## Usage

- To see the api in action, click on the video below to see the full demo usage of the back-end api.

[Usage video](https://drive.google.com/file/d/13JN558R6yvsmzauB7scM-9r8a-n5uTXu/view)

## License

MIT License

Copyright (c) 2023 JosePerez013

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.