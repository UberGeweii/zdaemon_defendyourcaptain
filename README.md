# zdaemon_defendyourcaptain
![TITLEPIC](https://github.com/UberGeweii/zdaemon_defendyourcaptain/assets/83827407/ecf030fa-a6a3-4c18-968e-74a2b2c9a203)

A new team-based gamemode for ZDaemon, it's not been tested with other ports!
I might make this compatible with Zandronum in the future.

# Gamemode description
How this it work? Well it's simple! One person of each team gets assigned "the Captain".
The others are assigned with the task of defending their captain. Your captain dies? the other team scores!
A captain can tank a lot more damage than a normal defender. So it'll take some serious effort to bring him down.

Always run this modification in CTF mode. It pretty much runs with any CTF .wad!
Thanks for checking out this mode!

# Recommended Settings
Game Mode: (CTF) DSC

IWAD: doom2.wad (or freedoom)

DMFLAGS: 1291866180 / 1074135040 / 128

Timelimit: 8 mins

Overtime: yes

Teamscorelimit: 10

Aircontrol: 0.00390625 // ZDoom

Teams: autobalancing

Skill: 4 // Nightmare!

sv_roundbased 0

sv_dmgfactormode 1

sv_alwaysnewcaptain 1

# CVars
sv_dmgfactormode (Instead of giving the captain extra health it's damagefactor is being altered, 0 or 1)

sv_debugmode (developer debugging, 0 or 1)

sv_maxhp (Set a captains starting HP, only has effect in non-dmgfactor mode, int: defaults to 300).

sv_captaindoublescore (Captain kill means the team scores 2 points, 0 or 1)

sv_alwaysnewcaptain (Experimental: always pick a new captain when one gets killed from either team, 0 or 1)

sv_roundbased (Experimental: mimics ZDaemons' round based system, 0 or 1)

sv_forceteamrespawn (Experimental: requires for sv_roundbased to be set to 1, respawns whole team when round ends)

sv_newroundonsuicide (Experimental: requires for sv_roundbased to be set to 1, calls a new round when a captain suicides)

# Impression 
![zds-823_screenshots](https://github.com/UberGeweii/zdaemon_defendyourcaptain/assets/83827407/39cbdb87-0c78-46df-b164-b95983009df8)


# Credits
Coding - UberGewei & AF-Domains.net

Health bar - Thank you Apothem - https://zdoom.org/wiki/Health_Point_Bar

Testing - Flambeau & The ZDaemon community

Screenshot .gif - Krawa
