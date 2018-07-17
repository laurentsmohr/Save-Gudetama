# Save Gudetama
> Welcome to the Save Gudetama typing game! 
>
> Play against yourself and beat your highscore or play online in multiplayer mode.

## Our Team
  - __Product Owner__: Laurents Mohr https://github.com/laurentsmohr
  - __Scrum Master__: Michael Cortez https://github.com/mchlcrtz
  
## Table of Contents

1. [Usage](#Usage)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
1. [Suggestions for further features](#Suggestions-for-where-to-go-from-here---take-or-leave!)

## Usage

> In MultiPlayer: You see other players in the lobby. You can either ask for random player matching or click on an online user, which will 
send a challenge request to that user. If the other user accepts, the game will start. In random player matching, the game starts as soon as another player is found.
> In Single Player you can set the difficulty level. Easier difficulties will have shorter words than harder difficulties.


## Development

### Installing Dependencies

From within the root directory:

```sh
sudo npm install -g bower
npm install
bower install
```
__Starting the Server:__
```sh
npm start
```
__Running Webpack/Starting Dev Environment:__
```sh
npm react-dev
```

### Suggestions for where to go from here - take or leave!
- Design improvements
- Button to toggle background music on/off
- Chat functionality
- Authentication for data persistence of user's high scores. (Currently anyone can log-in with any username.)
- PowerUps
- Different themes
- Different languages
