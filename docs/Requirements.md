# MasterMindBattle-Requirements

## Why
This project is created to practice the use of various tools to aid in API-Design first. In this example I am using Stoplight Studio from Stoplight.IO.

## API capabilities
The purpose of the API is to allow someone to write a client application, which would allow users to play two variations of MasterMind:  
- The standard variation, where the user plays against the computer  
- Another version where two users challenge each other, to whom can first solve the puzzle.

## User Stories
* As a user I would like to get a list of users, who are online
* As a user I would like to get some overall stats about the site
* As a user I would like to start a new game against the computer
* As a user I would like to make a "move" (guess or resign) and see the result
* As a user I would like to get a list of my current and completed games.
* As an admin I would like to see the status of all users and all games
* As an admin I would like to get notified of important events, such as user moves or new users joining the site.

## Some Data Models

```json
Game:
{
  GameId: "GameId01",
  Answer: [1,3,4,2],
  Rows: [
    {
      Guess:[1,1,1,1],
      NoOfRightColors:0,
      NoOfRightLocations:1
    },
    {
      Guess:[1,4,1,1],
      NoOfRightColors:1,
      NoOfRightLocations:1
    },
  ]    
}
```