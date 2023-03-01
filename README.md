# Bike portal

Project Name Bike portal
This project is a website with a login and contact us page that is connected to a database. The website is designed to be responsive to both desktop and mobile devices.

Technologies Used
Frontend: HTML,CSS,Reactjs,material-ui,
Backend: NODEJS,EXPRESS
Database: MONGODB,MONGOOSE,MONGODB-ATLAS

Features
Login and Logout functionality with Reactjs
contect mongodb atlas with nodejs for store the data of signin and signup page 

Responsive design for desktop and mobile devices
Installation
Clone the repository
bash
Copy code
git clone https://github.com/<username>/<project-name>.git
Create a virtual environment and activate it
bash
Copy code
python3 -m venv env
source env/bin/activate
Install the required packages
Copy code
Run the application
Copy code
python app.py
Usage

Register for an account or login if you already have one
Navigate to the Contact Us page and submit the form
Logout when finished
Credits
Bootstrap: https://getbootstrap.com/
Flask: https://flask.palletsprojects.com/en/2.1.x/
SQLite: https://www.sqlite.org/index.html
License
This project is licensed under the MIT License - see the LICENSE file for details.
```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md
```

## Instructions for initializing web app:

- Install Node JS, MongoDB in the machine.
- Start MongoDB server: `sudo service mongod start`
- Move inside backend directory: `cd backend`
- Install dependencies in backend directory: `npm install`
- Start express server: `npm start`
- Backend server will start on port 4444.
- Now go inside frontend directory: `cd ..\frontend`
- Install dependencies in frontend directory: `npm install`
- Start web app's frontend server: `npm start`
- Frontend server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.

## Dependencies:

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid


