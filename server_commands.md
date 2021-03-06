# Server Commands

To kick players from the server and to do other similar things, you have to use the server commands. This doc will show you these. If you want to know how to set up a server, read the [Server Setup](server_setup.md) doc. For server settings, see the [Server Settings](server_settings.md) doc.

### Commands

|Command|	Syntax|	Description|
| ------ | ---------- | -------- |
|`echo`|	echo text|	Print a text in console|
|`exec`|	exec file|	Execute the commands in the file|
|`kick`|	kick id|	Kick the user with the specified id directly|
|`ban`|	ban ip/id minutes|	Ban the ip from the server for the given time|
|`unban`|	unban ip|	Unban the ip|
|`bans`|	bans|	Show a list of bans|
|`status`	|status|	List the player's id, ip, name and score|
|`shutdown`|	shutdown|	Shut the server down|
|`reload`|	reload|	Reload the map|
|`record`|	record filename|	Start recording|
|`stoprecord`|	stoprecord|	Stop recording|
|`tune`|	tune variable value|	Tune the variable. See the [Server Tuning](server_tuning.md) doc|
|`tune_reset`|	tune_reset|	Reset the tuning to default|
|`tune_dump`|	tune_dump|	Make a dump that shows what tuning is used|
|`change_map`|	change_map mapname|	Change to the specified map|
|`restart`|	restart time|	Restart the round (time is optional)|
|`broadcast`|	broadcast text|	Broadcast the text|
|`say`|	say text|	Send a chat message|
|`set_team`|	set\_team client\_id team\_id|	Move a player to a specific team (0 = red, 1 = blue, -1 = spectators)|
|`set_team_all`|	set\_team\_all team\_id|	Move all players to a specific team|
|`add_vote`|	add_vote description command|	Add a vote option for the provided command with the provided description ( description is optional)|
|`remove_vote`|	remove_vote command|	remove a vote option|
|`force_vote`|force\_vote type option/player\_id reason	|Force a certain vote to be executed immediately (type can be "option", "kick" or "spectate")|
|`clear_votes`|	clear votes	|remove all vote options|
|`vote`|	vote yes/no|	Force the end result of the vote to yes/no|
