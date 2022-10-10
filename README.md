# text_editor

Description
This app was to install a text editor on or offline. It may become difficult sometimes to obtain service everywhere you go. So creating this text editor app can help when a user is offline. This app must meet PWA criteria this app is mostly used for offline users and has certian functionality that the browser does not support. Here is an image of what the app looks like.

Installation
In order to run the app you must clone the starter code. You will then need to run dependencies on both the client and server folder. You will run npm i and then you will run npm start. This will then run your app in your localhost. You will also need to deploy this app with heroku. Here is my heroku URL https://git.heroku.com/pwa-txteditor.git

Tests
This app can be tested in your localhost.

## Challenge:
Your task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

Acceptance Criteria
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


Worked with peer -- Diana Portillo

