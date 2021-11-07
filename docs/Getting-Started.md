# Getting-Started
This short guide will show you how to get started quickly using our master mind gaming engine.

## API Overview
The API offers all of the functions necessary for you to build your own site for offering master mind games, either as a single player game or as a battle between two players.

The Api is split into the following resources:
### Users
Using the /users endpoint:
* A logged in regular user user may get a list of all of the other users, currently online on the site.
* As the site administartor you may get a list of all of the registered users (online as well as off line).

### Games
The main purpose of the site is to offer games to online users. A logged in user may:
* Start a new game
* Once a game has been started, the user may make moves againts the game. The move can either be a guess or the user can give up.
* The user may also get stats on any of the ongoing games they are participating in.

### Info resources
To make your site a little more interesting, you may call the /sistestatistics resource, so get some information about the traffic on the site.

As an administrator you also have the option to call the /events resource to get ongoing information about what happing on the site across all users and games.

