# Working-with-WebApi-and-AngularJS
WebApi-AngularJS Demo.7z contains two zipped files named VS.zip and packages.zip. Create a new folder and extract the contents of both of these zipped files in to the newly created folder. 

Use the DB scipt file to create and insert values in to the required tables.

The visual studio solution contains two projects, and both of the projects are configured to be hosted in the "Local IIS". 
NOTE: These two projects may fail to load if the Visual studio is not opened in the admin mode.

The backend WebApi project is hosted with the URL http://localhost/WebApi-AngularJSDemo and the same is defined as a constant in the ApiConstants.js in the AngularJS UI project. Should you change the URL of the backend WebAPi project, make sure that the same is replicated in the ApiConstants.js file in the AngularJS UI project.

You might face issues while using action methods to handle Http PUT and Http DELETE verbs in the WebApi. Please refer the file "Important_Notes on Http PUT and Http DELETE.txt" for the possible issues and their resolutions.

ui-router is used in place of default angular router for routing.


