# Pratilipi-REST-API
***
##### DEPLOY LOCALLY
Following are some steps to run this Rest API locally, using your local MongoDB:
1. Initialize all the dependencies first by doing `npm i`
2. Make sure MongoDB is pre-installed on your local system. Create a local database named as **pratilipi**. Inside that DB, create a new user with user **test** and pwd **test123** with readwrite and dbAdmin role access.
3. Install **Nodemon** globally for running the API or simply use `node`(as you wish).
4. Once all this is done, simply run `nodemon server/server.js` in the root directory.
5. The REST API can now successfully be seen running at [Port 3000](http://localhost:3000/explorer)
