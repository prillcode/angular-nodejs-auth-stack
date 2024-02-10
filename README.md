## Overview

**/client** - Angular app runs on port 4200.  
**/server** - NodeJS Express server runs on port 4000.

Run `npm install` in both directories to install requirements as defined by package.json in those directories.  
Run `npm start` in both to launch client (port 4200) and server (port 4000).  

In the Angular Client app, remove or comment out the line below the comment:  
// provider used to create fake backend located in the /src/app/app.module.ts file.  

Then restart the Angular app and it will now send requests to the Node.js authentication API on port 4000.
