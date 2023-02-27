FakeSAMP/RAKSAMP
=
FakeSAMP is a fake client for SA-MP.
  
Current version: v0.8.6-0.3.7DL.  
Authors: jlfm, bartekdvd, P3ti.
Special thanks to balika011, .silent, n3ptun0.  

**Edited by: Cizaquita**

Download Latest
https://github.com/cizaquita/FakeSAMP/releases

SA:MP Target version: 0.3DL tested and working. 

--
### Client
**Available runmodes in the client:**
* 0 = RCON mode,
* 1 = Bare mode (doesn't spawn),
* 2 = Still mode (stays still at spawn position),
* 3 = Normal mode (stays still at a position),
* 4 = Follows a player,
* 5 = Follows a player with a vehicle.
  
**Available commands in the client:**
* !exit or !quit: exits client.
* !reconnect: reconnects the server.
* !reload: reloads settings.
* !runmode: sets current runmode.
* !players: shows list of players.
* !npcs: show list of NPCs.
* !login: login to RCON.
* !rcon: send an RCON command.
* !goto: go to players position.
* !gotocp: go to the current checkpoint.
* !autogotocp: toggle automatic checkpoint teleporter.
* !imitate: change imitate name.
* !vlist: shows list of vehicles.
* !vdeath: send vehicle death notification.
* !fu: send lost connection packet to server.
* !spawn: spawns fake player.
* !pickup: pick up a pickup by ID.
* !class: select a class.
* !menusel: selects an item from the GTA menu.
* !kill: toggle fake kill flooder.
* !lag: toggle server lagger.
* !spam: toggle reconnect spammer.
* !joinflood: toggle join flooder.
* !chatflood: toggle chat flooder.
* !classflood: toggle class selection flooder.
* !bulletflood: flood the server with bullet sync packets to the players' positions.
* !weapon: sets the current weapon in the fake player's hand.
* !selplayer: sets the followed player's name.
* !selveh: sets the fake player's vehicle.
* !pos: sets the fake player's position.
* !follow: sets the following offset.
* !pulsator: pulse health & armor.
* !change_server: connect to another server without restarting RakSAMPClient.
* !change_name: change the fake player's name and reconnect/rejoin the game.
* !diares: send a dialog response.
* !logstatus: show log status.
* !log: toggle logging objects/pickups/textlabels/textdraws.
* !teleport: show the teleport menu.
* !scmevent: send SCM event.
* !fakekick: send vehicle enter notification with invalid vehicle id to get kicked.
* !seltd: select a textdraw.
* !sendrates: show sendrates.

--
### Edit and Build instructions

1. Download C++ IDE http://download.microsoft.com/download/A/5/4/A54BADB6-9C3F-478D-8657-93B3FC9FE62D/vcsetup.exe
2. Open Solution RakSAMP_2008.sln
3. Edit, Debug

Enjoy!
