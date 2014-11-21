My-Denizen-scripts
==================
A collection of scripts, some of which I wrote from scratch, and some of which are re-writes of ones I found on the Citizens Script Repo.

Bossfight
---------
The original version of this was provided as a single script and published by mythanical on the Citizens Repo. As it was written for earlier versions of both Denizen and Sentry, I have extensively re-written this in order to get it working again with the current versions.  

In order to make it easier to have different Bosses configured on the same server, I have moved the scripts that only need to be provided once-per-server into a separate script - Bossfight_items_and_world_scripts.yml

The main functionality is in the file called 'NewMoonBoss.yml', it is now mostly functioning, with further bugfixes to come, and a to do list in the initial comments.

Moontimes.yml
-------------
A script of entirely my own creation, using the moonphases tag to (at the moment) provide formatted announcements of the moon's phase to certain groups of players, and time of day announcements to all players.  My ultimate intention is to use this to run a different Boss-fight on each phase of the moon in our quest world.

Jarvus|Iris|Dillion.yml
-----------------------
Each of these provides an interactive npc that accepts chat triggers to give a repeatable kill quest to players. (e.g. kill 10 Creepers).  The npc speech is formatted via an included format script, and the npc has several sections of randomised chat, so that interact doesn't become boring with repetition.

The scripts use a specific format of their flags, so that a command ('/quests') provided by the next script can provide players with a summary of where they are with each quest.

World_Utility_scripts.yml
-------------------------
This file provides scripts for two commands, the '/quests' command described above, and a '/spawn' command that returns players to checkpoints that have been set by another script. (available in the citizens repo.)

The file also contains a world script to give 0|1|2 (randomised) emeralds to players on killing hostile mobs, as we use emeralds as currency in our quest world.

Dad.yml
-------
A short script with working regex chat triggers, and formatted responses; used for an npc who greets new players to the world.

Where to find these scripts in action?
======================================
These scripts are part of Jewelcraft, the quest world on RemyPas.com, come visit us if you are interested.

