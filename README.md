# Secret-app-using-nodejs-express-js-Ejs-postgreSQL
1. Install all node modules using "npm instal"
2. Create new DB in PostgresQL in the name of "Secret" 
3. Create users table by using QUERIES in solution.sql in Secret DB
4. RUN the APP using command "nodemon index.js"

####note----if you want to create your own oAuth signin in Google
1. you'll first need to create your own credentials to use in the project.
2. Navigate to **https://console.cloud.google.com/ and sign in with your Google/gmail account**.
3. Access "Credentials" under APIs & Services(**Click on the hamburger menu and navigate to "Credentials**".)
4. Configure Consent Screen
(**Before you can create your credentials you'll have to configure the consent screen. You'll be prompted to do this when you click "Create OAuth Client ID", but there's also a tab on the side where you can do this right away**.)
5. Configure your Scope(**Scopes are the fields that you will receive once the user logs in through google. We're just interested in the email so click on "Add Or Remove Scopes". And add a checkmark**)
6. Create your client ID
(**Once your done, navigate back to "Credentials", click "Create Credentials - OAuth client ID**.)
7. Add localhost to your Javascript origins
8. Add localhost to your redirect URI
7. Copy your Client ID and Client Secret