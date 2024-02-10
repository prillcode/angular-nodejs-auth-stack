## Overview

This is a full stack Angular + NodeJS starter application with JWT token authentication scaffolding.  

## Getting Started

**/client** - Angular app runs on port 4200.  
**/server** - NodeJS Express server runs on port 4000.

- Run `npm install` in both directories to install requirements as defined by package.json in those directories.  
- Run `npm start` in both directories to launch client and server on their respective ports.

In the Angular Client app, remove or comment out the line below the comment:  
`// provider used to create fake backend`  
located in the /src/app/app.module.ts file.  

Then restart the Angular app and it will now send requests to the Node.js authentication API on port 4000.  

__  
  
[VIDEO: More explanation on this Stack](https://www.youtube.com/watch?v=DZ9LB9IFZ8U).
