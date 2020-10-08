# Budget Tracker

## Description
A Mobile-First, Progressive Web Application (PWA) Budget Tracker that allows a user to track income and expenses online and offline. This project was provided with most of the frontend features intact, I added offline capabilities, and online data storage. IndexDB allows for local storage of data if the internet connection is lost, with site data managed by an added service worker. When the connection is restablished, data created from work done in the interim is sent to the database. The Heroku Site's data is hosted on MongoDB Atlas. By clicking the plus sign in the url bar you can install an icon of the site on your machine.

**[Deployed Application](https://murmuring-scrubland-74158.herokuapp.com/)**
  
![Screen Shot 2020-10-08 at 4 17 33 PM (2)](https://user-images.githubusercontent.com/65192910/95514588-cf670b00-0981-11eb-86db-c0dea1e53626.png)

## User Story

```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

## Acceptance Criteria

```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```
   
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
`npm install`
  
## Usage
`npm start`

## Testing
No current testing

## Contributing
[Rachel Fritz](https://github.com/rachelf0)

## Questions
✉️ Contact me with any questions: [email](mailto:rachelfritz0@gmail.com) , [GitHub](https://github.com/rachelf0)<br />