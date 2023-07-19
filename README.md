# gmod_gravity_generator
This is my first Garry's Mod LUA Script Addon. Within it are four entities, three of which revolve around the Gravity Generator entity.  Please do not re-upload this repository. If you would like to make adjustments to some of the variables, to better acclimate the addon to your server's gameplay needs, be my guest. The models will not be available here to save time on downloads. If you would like to find them, you can download them from the workshop addon (https://steamcommunity.com/sharedfiles/filedetails/?id=3006668356).

The four entities are listed below with a thorough explanation of them along with an explanation of some elements of my code. While this addon is certainly not the neatest, nor probably the most optimized, it likely will stay this way, in part as a reference for future addons, and to show over time the transformation of my work, not just in scale, but programming methodologies, LUA expertise, etc.

Gravity Generator: Naturally over time has its fuel deplete and breaks down eventually. The two variables that keep track of that are timeElapsed and degredation respectively. 

Repair Kit: This has a chance to succeed, ideally to simulate a level of realism, being that sometimes repairs require more extensive work. Thus, there is a chance that initial repairs fail and may require multiple attempts. Upon a successful attempt, the user is rewarded with Dark RP money.

Fuel Cell: The fuel cell upon making contact through usage of the gravity gun increases the fuel supply. Upon complete refueling, the user is rewarded Dark RP money.

Sabotage Device: If the admins or gamemasters wish to damage severely the gravity generator, they can do it quickly using the sabotage device. Just like the fuel cell or repair kit, using the gravity gun, just have the entity make contact with the gravity generator.
