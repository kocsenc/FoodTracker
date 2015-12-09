# FoodTracker
A UX demo of a food tracker for Intro to Geospatial class.

# Disclaimer
This project is a high-fidelity prototype. It does not implement any business logic yet.
Additionally, this website was developed as a prototype of a native smartphone application, so layout on a desktop browser is non-optimal.

# Running the Application
A public version of the application is available at [here](https://food.rit.lol), but if you want to run it yourself follow the following instructions:

1. Install the latest version of ruby and gems (on Windows get ruby < 2.2)
2. Run `gem install bundle`
3. Clone the repo
3. From within the project directory run `bundle install` to install dependencies
4. To build and serve the application run `bundle exec jekyll serve` which will start a web-server on your local computer on port 4000 by default
5. Browse to [http://127.0.0.1:4000](http://127.0.0.1:4000) in the Google Chrome web browser.

# Features
The following sections are roughly in order for a good tour through the application.

## Log in
A login page is located at `/` and presents a username and password login interface with an option to join.

## Join FoodTracker
Located at `/join/` is a registration page that includes all the important information for user creation including name, email, and password.

## Feed
At `/list/` users will find a heatmap of reported trash in the local area and a list of pictures of recent local trash pickups. These pickups include a location button and a report button for illegitimate trash entries.

## Reporting Pickups
Illegitimate trash pickups can be reported at `/report/`. Users can enter a reason that this trash pickup should not be counted.

## Profile
Users can view their profile (including recent activity) at `/profile/`.

## Submit Pickup
From any page other than Login and Join, users can click the camera button in the upper right-hand corner to submit a new trash pickup. The route for this is `/submit/`. Users can tap the camera feed to take a picture and tap again to retake.
Users can then drag the trashcan icon on the map to set the location of the pickup and submit the pickup.


We hope you enjoy using FoodTracker!
