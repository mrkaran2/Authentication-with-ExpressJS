# User-session-and-authentication-with-ExpressJS
This project uses NodeJS, ExpressJS and Mongoose to illustrate working of user sessions and authentication. There are three pages: `/login`, `/registration` and `profile`. If a user is already logged-in then that user is always redirected to `/profile` page until logout button is clicked. I have not put any constrain on uniqueness of username, so a user can register with same username.  

# Setup Instructions
- Paste this code into your terminal - `git clone git@github.com/mrkaran2/User-session-and-authentication-with-ExpressJS.git`
- `cd` into `User-session-and-authentication-with-ExpressJS` and run `npm install`
- Run the node.js server using the command `node main.js`
- Open `localhost:9999` in your browser

