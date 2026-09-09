# Yale Explorer
An interactive point-and-click style game that lets you explore all (eventually) of Yale University.
This project aims to capture the majority of campus including secret areas you wouldn't normally know about... but you still have to find them yourself!

### Package System
Each building of campus has its own zip file that contains pictures for each room/corridor.
For example "o-fr.zip" contains assets for Old Campus — Farnam Hall.
Most importantly, each zip file contains an assets.json file that lists every room and the points in the room that can be clicked on to take you to adjacent room.
Yes, this took a lot of time, thank you for asking.
The important thing to note is that you can actually make your own packages and load them through developer mode (I'll let you figure out how to enable it.)

### Developer Mode Keybinds
|Key|Function|
|---|--------|
|W|Warp to a specific scene|
|A|Add a debug click point|
|S|Remove the most recent debug click point|
|C|Copy the current debug click points as a "points" key array|
|D|Remove all debug click points|
|J|Show all click points for the current scene while held|
|O|Open an asset zip file from local storage|
|1|Restart the project (if you loaded in new assets)
|6|Show the assets list (50% chance of not working because I'm lazy)|
|G|Deny access to everything while held|

### Importing an asset zip file
1. Enable Developer Mode
2. Press O
3. Enter the name of the asset (Ex: o-fr) or enter a link to a zip file hosted somewhere
4. Upload the zip file
5. Press 1 to restart the project with the resources applied
6. Use W to warp to your scene
Note: You will currently also need to override the assets.json for an existing file to get your asset to load since there is currently no keybind to load an asset pack

Disclaimer: Yale Explorer is not directly affiliated or associated with Yale University and is not an official yale.edu website.
