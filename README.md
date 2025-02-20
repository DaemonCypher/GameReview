# GameReview
A game review website that takes inspiration from IGN game review and reddit daisy chain threads replies.

# Prerequisite
* IGDB API Key
* Render SQL database

## App Info:
* App Link: [<https://project-1-big-chungus.onrender.com/>]()

# Collaborators
* Daniel Bielejeski
* Ezra Blake
* Crystal Wen
* William Yang
* Jinming Chen


## Key Features
* Child Parent topic/review chain (i.e. reddit thread)
* Incorporating and extracting data from IGDB API
* Fuzzy Search

## Website Preview
Home page showing recently reviewed and added games. The added games would be new games that was added from IGDB API.
![home](./screenshots/home.png?raw=true)


Game page displaying the cover art, title, and summary of the game from IGDB APi. Along with sub section for users to look and post review/topics.
![game](./screenshots/game.png?raw=true)


Profile page showing an default image is the user decides to not have a profile image, and brief descriptions about the user as well as how many reviews they left on the website.
![profile](./screenshots/profile.png?raw=true)


Result page displaying the fuzzy search results where the website is searching through both its database for topics/reviews and IGDB API based on the user query
![result](./screenshots/result.png?raw=true)


Review page showing a rating and review of a game left by users, as well as the child parent post chain.
![review](./screenshots/review.png?raw=true)

## Mock-up 

The home page of the website, displaying general user content
![Home Page](./mockups/homePage.png?raw=true)

A login page for users to login or create an account if needed
![Login Page](./mockups/loginandsignup.png?raw=true)

A page for the individual reviews/topics created by the users, has
discussion responses as well
![Review Page](./mockups/reviewandtopic.png?raw=true)

A page for a specific game, includes different reviews and topics about the 
game
![Game Page](./mockups/gamepage.png?raw=true)

A page for the user profile
![User Profile](./mockups/userProfile.png?raw=true)

A page for the user settings
![User Settings](./mockups/settings.png?raw=true)

Link to Figma project:
https://www.figma.com/design/yl4nxmAKSPm4ww1B2vN6j5/GameReview?node-id=49-2361&t=hzYgSGKvHp1r1xso-1

## External Dependencies
* IGDB API: used to grab relevant game data (i.e. name, genre, summary, cover art)
