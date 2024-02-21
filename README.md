Work in progress "Checkpoint System" for Barony, it's more of a save scum version of the game, where the saves dont delete themselves once all players die. I created a solo verion of the mod here in python: https://github.com/Sat727/Barony-Checkpoint-System.


# What it does

The modifications to the EXE for now disables the packet sent to players connected to the server to delete the savefile/game over, and prevents the client itself from deleting the savefile resulting in no progress loss once all players die. Maybe there will be a feature in the future to restart the level, but for now you will need to go to main menu and re-host the game

# How to setup

Simply download the .exe file located at [https://github.com/Sat727/Barony-Checkpoint/releases/tag/exe](https://github.com/Sat727/Barony-Checkpoint/releases) and place it in your barony root folder. You do not have to replace your current barony exe, you can name it something like "modified.exe". Please note, in order to play multiplayer, you WILL need to port forward with the same port you have the game configured to, by default it is 57165 via TCP. Then run the game on local host. If you have any issues, feel free to create an issue post.
