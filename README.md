# mern-dating-app-project
Following the project from Nabendu Biswas's MERN Projects book

All the codes here are followed based on the book in this link:
https://www.amazon.com/MERN-Projects-Beginners-MongoDB-Express-js/dp/1484271378


---Front-end---

To run the app, ensure dependencies are installed namely, run:
npm i @material-ui/core
npm i @material-ui/icons

With npm present, npm start inside the front-end directory should at least execute the React app

---Back-end---

Requires setting up the DB and updating the MongoDB url in server.js inside backend folder
The idea is that you run two servers - one for backend (MongoDB/Express) and one for frontend (React), and two cross talk via axios
