# PWA---Text-Editor
## Description
JATE is a text editor that runs in the browser. Its a single page application that meets the PWA criteria. It could be useful for developers to create notes or code snippets with or without internet connection so that they could reliably retrieve them for later use.

#### Table of Contents

-[Installation](#installation)

-[Usage](#usage)

-[Technologies used](#technologiesused)

-[User story](#userstory)
-[Deployed Link](deployedlink)

## Installation
This program can be run through a browser using the link to the the deployed application. Alternatively, to run this application locally you will need to:

Clone this repository to receive all of the files.

Run "npm install" in the command line of your terminal to set up all of the dependencies.

Run "npm start" to start the backend and serve the client.

Go to the url of the application (http//:localhost:3000) to begin using it.

## Usage
As you have progressed through this course, you have put together a number of impressive projects that you can show off to potential employers. 
Text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this text editor, use an existing application and implement methods for getting and storing data to an IndexedDB database.Use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.If the Install button is clicked, the web application will be downloaded as an icon in your desktop.
The application works without an internet connection.

## Technologies used
Node.js, Express.js, IndexedDB, PWA, Heroku

## user story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application


## Deployed Link
https://git.heroku.com/stark-headland-40665.git



