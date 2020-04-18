# mc-server

# A vanilla 1.15 Minecraft server - hosted on Heroku

Set this up when I got sick of using Hamachi as a *fake* `local area network` to be able to play with friends on our Minecraft server. Uses the Fantastic [Heroku Minecraft Buildpack](https://github.com/jkutner/heroku-buildpack-minecraft) so pretty much all the code is happening on Heroku.

## Want to play with us?
The ip for the server is refreshed quite often, so check in on https://shrouded-caverns-32037.herokuapp.com/ to see what the current one is.
> Since it's hosted on Heroku- if nobody's used the link for an hour- the app is asleep. That'll cause it to load very slowly. Subsequent loads are significantly faster.

## User management
The `.json`-files in the repository can be used to ban/whitelist people or IP addresses.

## Playability 

Server specific restrictions to gameplay, game mode or changes to server settings is edited through the server.properties file. 
