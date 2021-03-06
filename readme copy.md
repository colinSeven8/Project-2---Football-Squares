# Project Title: NFL Pick 'Em

## Google Slides Presentation
https://docs.google.com/presentation/d/1SvWemIAWIRDnifAGaSY_YCe023D0SMpBczxvTwKJmCk/edit?usp=sharing

## Try The App Out Here:
https://nflpickem123.herokuapp.com/


## Team Members:
RJ Pupunu, Colin Reesor, Xander Canedo, Brennen Bates

## Technology Used:
HTML, CSS, Bootstrap, Javascript, Jquery, Handlebars, MySQL, Sequelized, Heroku, JawsDB, MVC, Axios

## New Javascript Libraries: 
1. JSON Web Token (jwt) - used for user authentication
2. BCRYPT - used to encrypt passwords when saving user data

## APIs used:
NFL Game Data:
1. https://feeds.nfl.com/feeds-rs/scores.json
2. http://www.nfl.com/liveupdate/game-center/2018102107/2018102107_gtd.json

## Project description:
This app allows you to create pick em forms for NFL games so that you can bet on the games with your friends.  Typically these forms are printed out and passed around at parties or gatherings, people buy a certain number of squares and put their name on the sheet.  

This app has user authentication allowing a new user to sign up.   They then can click on View This Weeks Games to see all of the NFL matchups for the week.  This data is pulled from the NFL apis listed above.   They can then click on a game which saves it in their user games.  Then they can click View Your Games and then select into that game.  After that the form shows up.  They can then input names into each of the cells and click a button to save this data for future use.
