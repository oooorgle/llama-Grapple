llama-Grapple 1.5 for Minecraft 1.8
=============
A simple yet customizable grapple hook for Minecraft!

Features
    Easily manage custom configurations for privileged, donating, or ranked players.
    Set the tool or item used as the grapple hook.
    Set the sound the grapple makes.
    Set the distance the grapple will pull from. (max 100 blocks)
    Set the cool-down between grapple uses.
    Set the vertical-gain (elevation) of the grapple.
    Enable/Disable grapple hook durability.
    Enable/Disable grapple use for blocks below the player.
    Use Minecraft Time or System Time. For servers that turn time off or use the "/gamerule doDaylightCycle false" gamerule.


Command | Description | Permission

/lgrapple | Gifts the grapple hook. Right click to use it.	| llamagrapple.grapple
  Permission needed to use the grapple hook.	| llamagrapple.grapple
  Permission needed to craft the grapple hook. | llamagrapple.craft

/lgrapple on|off | Disables notifications of durability and cool-down. | llamagrapple.grapple

/lgrapple status (playername) | Display the status of a players config settings. Leave (playername) empty to display the default group. | llamagrapple.config

/lgrapple distance # (playername) | Set the distance the grapple will reach. Leave (playername) empty to set the default distance. This will create player settings if none exist. | llamagrapple.config

/lgrapple cooldown # (playername) | Set the cool-down between grapple uses. Leave (playername) empty to set the default cool-down. This will create player settings if none exist. | llamagrapple.config

/lgrapple gain # (playername) | Set the vertical gain when grappling. Leave (playername) empty to set the default gain. This will also create the players settings if none exist.	| llamagrapple.config

/lgrapple remove (playername) | Remove a players grapple settings. | llamagrapple.config

/lgrapple reload | Reload the configuration file. |	llamagrapple.config

/lgrapple durable | Toggle durability reduction on grapple hooks.	| llamagrapple.config

/lgrapple time | Toggle between using Minecraft Time or System Time. | llamagrapple.config

/lgrapple below | Toggle grapple use for blocks below the players.	| llamagrapple.config


Examples
/lgrapple gain 3 oooorgle
Sets the vertical gain for player oooorgle to 3.

/lgrapple distance 20
Sets the distance for the Default grapple to 20 blocks.

/lgrapple distance 20 oooorgle
Sets the grapple distance for player oooorgle to 20 blocks.

/lgrapple off
Disables notifications of durability and cool-down for the player sending the command.

/lgrapple remove oooorgle
Removes oooorgle's custom grapple settings.

/lgrapple status practiclycrp
Displays settings for player practiclycrp.

/lgrapple
Gifts you the grapple hook.

Crafting the grapple hook in survival is as easy as making the tool, then naming it 'grapple hook' in an anvil.
If you have set an item that doesn't need crafting, like log or diamond, simply name the item the same way in the anvil.


Configuration
    Copy the .jar to your plugins folder and restart your server.
    Add permissions to your groups and players.
    Log in and type '/lgrapple' to start grappling.
    
Optionally:
    Disable notification of new updates for this plugin by changing NotifyOpsWhenPluginUpdates to false in the plugins/llamaGrapple/config.yml.
    Configure the gain, distance, and cool-down for each permission with in-game commands or by editing the config.yml.
    Configure the sound, grapple item, and default notification settings by editing the config.yml.
