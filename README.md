# J.A.T.E (Just Another Text Editor)

J.A.T.E (Just Another Text Editor) is a progressive web application (PWA) that allows users to edit and save text in the browser. It meets several criteria to ensure a smooth user experience, including client-server folder structure, bundled JavaScript files, IndexedDB database storage, service worker registration, and caching of static assets.

# Features

 - Client-server folder structure is visible when the application is opened in the editor.
 - Running npm run start from the root directory starts up the backend and serves the client.
 - JavaScript files are bundled using webpack.
 - Running webpack plugins generates an HTML file, service worker, and a manifest file.
 - Next-gen JavaScript can be used without errors.
 - IndexedDB immediately creates a database storage for saving and retrieving text content.
 = Content in the text editor is saved with IndexedDB when users enter content and click off of the DOM window.
 - Content in the text editor is retrieved from IndexedDB when the text editor is reopened after closing.
 - Users can download the web application as an icon on their desktop by clicking the Install button.
 - A registered service worker is used using workbox.
 - Static assets are pre-cached upon loading and subsequent pages.
 - Proper build scripts for a webpack application are included for deployment to Heroku.
# Install

To get started with J.A.T.E, clone the repository and run ```npm install``` to install dependencies. Run ```npm run start``` to start up the backend and serve the client. Open a browser and navigate to the provided URL to use the text editor.

# Deployment 

[Link](https://jate-pwa-bako.herokuapp.com/)

# Screenshot
![Screenshot 2023-02-26 142814](https://user-images.githubusercontent.com/112914389/221438487-97c82fe4-b450-4a66-9a24-cd34a4b6dc4c.jpg)
