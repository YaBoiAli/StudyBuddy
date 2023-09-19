# StudyBuddy

## Description

This is a full stack webapp that allows users to create and share flashcards. It was created for people to come and share study notes with one another. It utilized [MongoDB](https://www.mongodb.com/) with [Graphql](https://graphql.org/) and [Apollo](https://www.apollographql.com/docs/) to handle the database. The webpage is built using [React](https://react.dev/), and styled with [animate.css](https://animate.style/), and [typewriter-effect](https://www.npmjs.com/package/typewriter-effect). It also utilizes [jsonwebtoken](https://jwt.io/) and [bcypt](https://bcrypt.online/) to handle user logins. This application was deployed using Heroku, you can check it out here [Heroku]([https://www.heroku.com/platform](https://study-buddy-p3-0d14fa2a37d6.herokuapp.com/)).

## Table of Contents

- [StudyBuddy](#studybuddy)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Usage](#usage)
  - [License](#license)
  - [Future Development](#future-development)
  - [Authors](#authors)

## Usage

This is the [url](https://study-buddy-p3-0d14fa2a37d6.herokuapp.com/) for the homepage. To use this application, you would first need to log in or create a user account by either clicking on the “study now” button at the center of the page, or go to “login/signup” in the navbar at top of the page. Once logged in, you will be taken automatically to the main page where you can see all the flash card decks created by all users. Clicking on the deck will allow you to view the cards that are inside the deck. Each card will have a “term” side and “definition” side, and clicking on the card will allow you to “flip” the card. Right and left arrow key will allow you to navigate through the cards. If you are the creator the deck, you can click on the “edit cards” button below the card to edit the cards inside the deck.
Clicking on “User Page” on navbar will allow you to see the list of decks you made. Clicking on “Create New Card set” button will allow you to create a new deck of cards.
“Logout” button on navbar will allow you to logout, returning you to homepage.

![studyBuddy main page with all decks](https://github.com/Marinah1031/StudyBuddy/assets/126653060/096ad632-eaec-4463-8565-b113cf4c2b25)

![Card page to display card term](https://github.com/Marinah1031/StudyBuddy/assets/126653060/f461f307-7746-4315-8be5-fa2954c49e0b)

![Deck editing page](https://github.com/Marinah1031/StudyBuddy/assets/126653060/1d0510cd-e210-46fe-ac34-4efb51821bbf)


## License
  
[![license](https://img.shields.io/badge/License-MIT-green)](https://choosealicense.com/licenses/mit/)

## Future Development

- Add search/filter feature to main page.
- Add a feature to favorite a user.
- Add feature to favorite a deck.
- Add a functioning “forgot password” button to handle user credential editing.
- View/Hide feature for card to skip certain card you no longer want to view.
- Create more options for how users can view and navigate through the cards.


## Authors

- Alex Nguyen [@monstergog](https://github.com/monstergog)
- Keiji Onishi [@meekunn1](https://github.com/meekunn1)
- Marinah Tamura [@Marinah1031](https://github.com/Marinah1031)
- Muzzammil Nawab [@YaBoiAli](https://github.com/YaBoiAli)
