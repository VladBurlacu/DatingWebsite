## Steps for building the website

1. Setting up the website's infrastructure
   - [x] Choose a web hosting service (e.g. Heroku)
   - [x] Set up the development environment (PHP, Composer)
   - [x] Create a new Laravel project
   - [x] Set up the web server on Heroku
   - [x] Configure the database (MySQL)

2. Designing the website
   - [ ] Create wireframes for the necessary pages.
      1. Homepage
      2. Account creation
      3. Account profile
      4. The chat box
      5. About us page
      6. Contact form
   - [ ] Create a basic layout for the homepage.
   - [ ] All the pages must have the same navbar
   - [ ] Use a parallax in the homepage with 3 slides:
      1.  "How does it work?" slide that explains how the matching system works.
      2.  "Join now!" slide which will lead to the account creation page.
      3.  "Get unlimited matches!" slide which will be the option to buy a subscription and upgrade your account, thus gaining unlimited matches.

3. Implementing user authentication and registration
   - [ ] Create a registration form for users to sign up
   - [ ] Implement email verification for new users
   - [ ] Implement age and location filters on the user registration form
   - [ ] Implement password encryption
   - [ ] Create a login form for users to sign in
   - [ ] Implement password reset functionality
   - [ ] Add terms of service to make sure the users are legal adults

4. Implementing the "Go on a Blind Date" feature
   - [ ] Shuffle all the active users and connect 2 random people together in one chat room
   - [ ] Add a text chat feature
   - [ ] Add a voice call or short voice message feature
   - [ ] Implement a limit of 3 matches per day for free users
   - [ ] Implement a VIP subscription to increase the match limit

5. Implementing additional features
   - [ ] Add a chat filter to mask bad words or eventually ban people who use bad words
   - [ ] Add a "Matched with" section that shows everyone you matched with, but no pictures, just their names and when you click on their name you can re-open the chat
   - [ ] Website needs to be responsive
   - [ ] Add a navigation bar with the following buttons:
      * Home
      * About us (with detailed instructions about the process)
      * Login/Logout button
      * Create account button (only appears when the user is not logged in)
   - [ ] Register a domain name
   - [ ] Point the domain name to the Heroku server's IP address

### Note: This is a work in progress, and as such, I will continuously update this file.