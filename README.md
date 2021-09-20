# cluck-backend-lightweight
Node Javascript CLUCK Backend API that updates the spreadsheet lab hours formula

## Intro
While the V1 CLUCK Java backend used MongoDB to store hours data, this server only tracks who is logged in at the current moment and the time they logged in (loggedin.json). When a user logs out, the server adds the time to the user's google sheet cell formula.

## Setup

 1. Clone this repo into its own folder
 2. Install node dependencies: `npm i`
 4. *(optional)* Edit the `server-port` variable in *./consts.js* *(default is 4000)*
 5. Ask Micah for `client_secret.json` file for google sheets
 6. Run server with npm forever `forever start index.js`
