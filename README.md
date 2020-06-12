# MeetingTracker-MEANStack
Full Stack Web App built using MEAN Stack

Install dependencies with 'npm install'.
To start front-end Angular dev server run 'ng serve'.
To start back-end NodeJS dev server run 'npm run start:server' to start nodemon.

Features:
Clean and responsive UI using Angular Framework and related modules.
CRUD operations on meeting posts.
User authentication using JWT.
Backend password encryption using bcryptjs.
Authentication Guard - Cannot see posts without logging in.
E-Mail received by all attendees, when meeting is created/updated using nodemailer.
Meeting Post visible only to the person who created it.
Frontend is served with REST APIs written using ExpressJS framework for NodeJS in the backend. 


Modules/Dependencies used: nodemon (dev only), bcryptjs, rxjs, uuid, path, http, mongoose, nodemailer, jsonwebtoken, body-parser, angular cli, angular material
