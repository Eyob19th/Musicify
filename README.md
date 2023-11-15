# Musicify
musicify  is a web app which uses spotify developer APIs and lists your most listened songs, albums, artists and genres.
#Tech Stack

React NodeJS JavaScript Spotify
#SETTING UP

    Fork the repo to your account.
    Clone the repo to your local computer git clone <fork url>
    Make sure Node js is installed on your machine (Node >= 14.0.0 and npm >= 5.6)
    cd into the project directory and run npm install
    Login or create an account at the Spotify Developers Dashboard.
    Click on the Create an App button in the spotify developers dashboard. Fill the details and submit.
    Note down the Client ID of the app just created.
    Go to your app Edit Settings and add http://localhost:3000 as a redirect URI.
    Create a file named .env.local at the project root directory with the following content:
REACT_APP_CLIENT_ID=<YOUR CLIENT ID>
Replace <YOUR CLIENT ID> with the one you got from the spotify console.
Now run npm start
#Folder structure 
├── src/
    ├── Pages/              Code for the pages
    ├── components/         UI Components
    ├── config/             API configs
    ├── styles/             CSS Files
    #Resources
    This project uses the Spotify Web API to get all the spotify related data.
    
