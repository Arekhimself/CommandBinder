Fork from https://github.com/Creepercraft206/CommandBinder
Full credit to original author. Thx !

<h1 align="center">CommandBinder</h1>
<p align="center">
    <img src="https://www.spigotmc.org/attachments/cb-icon-png.812903/" width="150" />
</p>

## Overview
CommandBinder is an all-in-one tool for every server. With simple to use commands and a wide range of possibilities, serverowners can modify items to their ever need.

Requirements:
- Permissionsystem (e.g. LuckPerms) with commands to give and remove permissions

This Plugin also supports PlaceholderAPI, allowing you to use your favorite placeholders also in CommandBInder!​

## Commands

Main command: /commandbinder or /cb
- × `/cb add <command>` » Adds a command to the holded item
- × `/cb remove <id>` » Removes the command with the specified id
- × `/cb insert <id> <command>` » Inserts the given command at the given id
- × `/cb set <id> <command>` » Override a command at the given id
- × `/cb list` » Lists all commands of the holded item
- × `/cb use` » Executes all commands from the item
- × `/cb onetimeuse <true/false>` » Toggles if the item should be consumed on use
- × `/cb confirm <true/false>` » Toggles a inventory to confirm the action
- × `/cb cooldown <cooldown>` » Adds a cooldown for using the item
- × `/cb addperm <Permission>` » Adds a permission to the item
- × `/cb removeperm <Permission>` » Removes a permission from the item
- × `/cb listperms` » Lists all permissions of the holded item
- × `/cb placeholders` » Shows a list of placeholders that can be used in an added command
- × `/cb customcmds` » Shows all custom commands
- × `/cb help` » Shows all commands from CommandBinder
- × `/cb info` » Displays information about the plugin

## Custom Commands

Apart from adding normal commands, CommandBinder also provides custom functionalities. (More will be added soon)
- × `!wait <seconds>` » Delays the execution of the following commands by x seconds
- × `!repeat <times>` » Repeats the following commands x times
- × `!endrepeat` » specifies the end of a !repeat command
- × `!if <condition>` » Only executes the following commands if the condition is true
- × `!endif` » specifies the end of an !if command
- × `!broadcast <message>` » Sends a global message
- × `!text <message>` » Sends a private message to the player
- × `!actionbar <message>` » Sends a message in the actionbar of the player
- × `!sound <sound>:<volume>:<pitch>` » Plays the sound for the player

## Placeholders

You can insert placeholders in commands of an item to get the current value of something. (More coming soon)
- × `%player%` » The player's name
- × `%UUID%` » The player's UUID
- × `%world%` » The name of the world the player is in
- × `%x%` » The player's x-coordinate
- × `%y%` » The player's y-coordinate
- × `%z%` » The player's z-coordinate
- × `%yaw%` » The player's yaw
- × `%pitch%` » The player's pitch
- × `%item%` » The name of the item in the player's hand
- × `%amount%` » The number of the item in the player's hand
- × `%slot%` » The slot of the item in the player's hand
- × `%durability%` » The durability of the item in the player's hand
- × `%playersOnline%` » The number of players online
- × `%block%` » The name of the block the player is looking at
- × `%lookingAt%` » The coordinates of the block the player is looking at
- × `%year%` » The current year
- × `%month%` » The current month
- × `%day%` » The current day
- × `%hour%` » The current hour
- × `%minute%` » The current minute
- × `%second%` » The current second
- × `%entityuuid%` » The UUID of the entity the player is looking at
- × `%entityname%` » The name of the entity the player is looking at
- × `%entitytype%` » The type of the entity the player is looking at
- × `%entityx%` » The x-coordinate of the entity the player is looking at
- × `%entityy%` » The x-coordinate of the entity the player is looking at
- × `%entityz%` » The x-coordinate of the entity the player is looking at
- × `%entityyaw%` » The yaw of the entity the player is looking at
- × `%entitypitch%` » The pitch of the entity the player is looking at
- × `%randomNum:<from>-<to>%` » Generates a random number in the given range
- × `%score:<score>%` » Returns the given score value
- × `%math:<expression>%` » Calculates the given expression
- × `%math:if(<condition>,<true>,<false>)%` » Return the true or false value based on the condition​

## Support
If you have any questions about the plugin, you found a bug or have an idea for a future update, feel free to write me on Discord or open a GitHub Issue.


This Plugin is still in development so please don't leave a bad review if something doesn't works completly. Just tell me what the problem is and i will try to fix it as fast as possible :) Thank you ^^
