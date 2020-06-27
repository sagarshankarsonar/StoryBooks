<h1>StoryBooks</h1>
Create public and private stories from your life
This app uses Node.js/Express/MongoDB with Google OAuth for authentication

<h2>Usage</h2>
Add your mongoDB URI and Google OAuth credentials to the config.env file

#Initiation
npm init

# Install packages
npm i express mongoose connect-mongo express-session express-handlebars dotenv method-override moment morgan passport passport-google-oauth20

npm install -D nodemon cross-env

# Install dependencies
npm install

# Run in develpment
npm run dev

# Run in production
npm start