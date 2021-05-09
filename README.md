# Redux Shop-Shop

Hello, and welcome to my README! This is for my Week 22  Challenge, which was to refractor existing code for a shopping app to use React Redux for state management. 

It was my job to ensure the Shop-Shop app had the following features:

- Use Redux to manage global state
- Use Redux instead of the Context API


I was to use Redux to manage global state, and meet all of the requirements listed above, by using:

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Heroku](https://heroku.com)
- [Redux](https://www.npmjs.com/package/redux)
- JavaScript
- HTML
- CSS

I completed this project as a way to continue working on my skills using React and Redux. 

Features:

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [Learning](#learning)
* [License](#license)

## Installation

The user must clone all files from this repo. It is important that the location of the files is not changed. 

The user must have [Node.js](https://nodejs.org/en/download/) and [MongoDB](https://www.mongodb.com/try/download/community) installed on their computer. 

The user must open the terminal, both command line and powershell will work, then enter "npm install" to download all the required dependencies. This must be done in the root of the project directory, in the "server" folder, and the "client" folder.This will allow the user to run the application as intended. 

To run the application, user must enter "npm start" in the command line in the root of the project. This will the backend and frontend servers. 

The localhost must then be opened on a web browser. This version of the website will only be available to the user on their own computer. 

Alternatively, the application can be viewed anywhere from [Heroku](https://infinite-journey-75983.herokuapp.com/)

## Usage
Here are some user experience highlights from my page:

The user is able to add and remove material from their shopping cart. Using [stripe](https://www.npmjs.com/package/stripe) they will be able to pay for their items and checkout. 

![adding and removing from cart]()

## Credits
These are some sources I used to help me along:

- [Node.js](https://nodejs.org/en/download/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [mongoose](https://mongoosejs.com/)
- [stripe](https://www.npmjs.com/package/stripe)
- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/tutorials/fundamentals/part-1-overview)
- [Heroku](https://heroku.com)
- [Invalid Hook Call Warning](https://reactjs.org/warnings/invalid-hook-call-warning.html)

  
## Learning
Here are the highlights of what I learned and issues I had while writing this code.
- Still getting the hang of working with two seperate servers while in development. Was also getting confused with the three seperate package.json files which needed different specific dependencies. 

- I was having a problem setting up my database for a while, then I realized that the MongoDB server was not just running in the background, I had to manually start it by running "mongod" in the command line. Once I did that I didn't have anymore issues. 

- I kept getting an error for an "Invalid Hook Call", it caused me some issues and then I realized that I was not calling a function properly, I had forgotten the "()" at the end of the function name 🤦

## License
MIT License

![license](https://img.shields.io/static/v1?label=license&message=MIT&color=blueviolet)

Copyright (c) 2021 Devin Jones

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.