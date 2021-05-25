# EternalJK - MBII Custom Edition Is A Full Client-Side Addon ! 
Credits to EternalJK developers for the massive sets of features.

# First Release !
# Known Issue:
Alt tab/Windows key is broken and won't minimize the game, use /minimize console command temporary 😢

## Features
+ Does Not Unlock Cheat Cvar(s).
+ Set A Custom Model Based On The Class (Open/Semi-Authentic/Duel).
+ Set Your Favorite Saber Color in all simplicity.
+ Set Jedi/Sith Saber Color.
+ Timenudge limitation removed (Useless since the introduction of Automatic Ping Based Timenudge)<br/>Use the new cvar "Custom_AutoTimeNudgeFactor"
+ Automatic Average Ping Based Timenudge (Multithreaded), ideal for duelist or gunners that seek victory at the cost of seeing entities choppy.
+ cl_maxpackets limit increased from 1000 to 5000 (unless the server deny it).
+ Disable the annoying flood of voice&gesture commands in your lower chatbox.
+ r_picmip has been reworked in a way that it now affect only the map textures😂 (funnily eJK implementation was very similar, i guess there wasn't many solution 😂)
+ Awesome EternalJK Features and Discord/Steam Integration.
+ All the features bellow (my Addition)

# Upgraded Windows Libs
EternalJK was somehow a bit outdated but it's okay, i took some minutes to update Libpng,Libjpeg,Zlib,SDL2, jesus linux is easier for that u_u.

# Note
All EternalJK new Cvars aren't listed here, only my new addition are documented<br>You might need to get used to that engine.

## How it work ?
It manipulate the Configuration sent from the server and finally rebuild the state of the game.

It may have delay in updating, if you wish to not wait a new round then go to the menu and toggle force model on/off.

That should refresh the game state without the need of waiting.

**It doesn't touch anything in cgame,ui dll's it's completely legit and doesn't touch anything related to MBII Code !**

# Installation
Simply Extract in your GameData folder and replace, if the launcher ask for updated files it may delete it and download their "own version of the engine".

In MBII Launcher select "Settings" -> "Engine" -> then choose "MBII Client" finally hit the play button, have fun <3

# 5 Important General Cvars (On/Off)
|Name|Default Value|Description|
|----|-----|-----------|
|Custom_Mdl_Enabled|0|Force Specific Mb2 Class To Use A Specific Model <0=Disabled 1=Enabled>|
|Custom_My_Mdl_Enabled|0|Override Your Model <0=Disabled 1=Enabled>|
|Custom_Saber_Enabled|1|Enable Custom Saber Color For Yourself <0=Disabled 1=Enabled>|
|Custom_Jedi_Saber_Enabled|0|Enable Custom Saber Color For Jedi <0=Disabled 1=Enabled>|
|Custom_Sith_Saber_Enabled|0|Enable Custom Saber Color For Sith <0=Disabled 1=Enabled>|

Keep in mind that using any custom model that's not a validated one will make you have no class

# Models Cvars
|Name|Default Value|Description|
|----|-----|-----------|
|Custom_My_Mdl|t_yoda/vendar|Override your model with <Model/Skin> Using FA Model work but will remove your actual class ...MB2Devs...|
|Custom_Mdl_ImperialSoldier|battledroid/command|Force Imperial Soldier class to use a specific model. <Model/Skin>|
|Custom_Mdl_RepublicSoldier|rebel/default|Force Republic Soldier class to use a specific model. <Model/Skin>|
|Custom_Mdl_Commander|Tarkin/default|Force COMMANDER class to use a specific model. <Model/Skin>|
|Custom_Mdl_EliteTrooper|s1_panaka/default|Force ELITE TROOPER class to use a specific model. <Model/Skin>|
|Custom_Mdl_Sith|desann/default|Force SITH class to use a specific model. <Model/Skin>|
|Custom_Mdl_Jedi|Kyle/default|Force JEDI class to use a specific model. <Model/Skin>|
|Custom_Mdl_BountyHunter|reelo/default|Force BOUNTY HUNTER class to use a specific model. <Model/Skin>|
|Custom_Mdl_Hero|leia_anh/default|Force HERO class to use a specific model. <Model/Skin>|
|Custom_Mdl_SBD|sbd/rocket|Force SUPER BATTLE DROID class to use a specific model. <Model/Skin>|
|Custom_Mdl_Wookie|chewbacca/default|Force WOOKIE class to use a specific model. <Model/Skin>|
|Custom_Mdl_Droideka|droideka/default|Force DROIDEKA class to use a specific model. <Model/Skin>|
|Custom_Mdl_CloneTrooper|clonesenate/captain|Force CLONE TROOPER class to use a specific model. <Model/Skin>|
|Custom_Mdl_Mandalorian|mbmandy2/maulmando|Force MANDALORIAN class to use a specific model. <Model/Skin>|
|Custom_Mdl_ArcTrooper|clonerc2/scorch|Force ARC TROOPER class to use a specific model. <Model/Skin>|

# Saber Customization Cvars
|Name|Default Value|Description|
|----|-----|-----------|
|Custom_Saber_Color1|255 255 255|R G B 1st Color Blade For yourself|
|Custom_Saber_Color2|255 255 255|R G B 2nd Color Blade For yourself|
|Custom_Jedi_Saber_Color1|0 0 255|R G B 1st Color Blade For Jedi|
|Custom_Jedi_Saber_Color2|0 0 255|R G B 2nd Color Blade For Jedi|
|Custom_Sith_Saber_Color1|255 0 0|R G B 1st Color Blade For Sith|
|Custom_Sith_Saber_Color2|255 0 0|R G B 2nd Color Blade For Sith|

[Pick your color as Hue Saturation Lightness and input the R G B accordingly](https://www.w3schools.com/colors/colors_hsl.asp)

# Notification
|Name|Default Value|Description|
|----|-------------|-----------|
|Custom_Notification|0|Disable Voice Chat And Gestures Notification of the chatbox if set to 1|

# Networking
|Name|Default Value|Description|
|----|-------------|-----------|
|Custom_AutoTimeNudgeFactor|0|if set, enable average ping based timenudge, grant faster response time, at the cost of making players choppy<br/>0=Disabled<br/>1=Enabled|

### Documentation
All new cvars are prefixed by **Custom_** You can write **Custom_ and press TAB** in your console.

To have a nice printing of all Cvars you can use the new command **Custom_ShowHelp**.
