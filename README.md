yuki.cfg
========
high-fps competitive csgo config

autoexec.cfg is used to "load" the config
yuki.cfg contains commands
userconfig.cfg contains binds
keyhelp.cfg contains a keymap over buybinds

some commands are useless without the binds and viceversa, and some binds need to be changed in both yuki.cfg and userconfig.cfg if you are going to change them.

you might want to make changes to "preference_commands" at the top of yuki.cfg. further tinkering with the config beyond this likely requires some basic understanding of how source-engine configs work/look like. feel free to ask me if you need any changes made.

added binds
========
![Image of Non-Default Binds](https://steamuserimages-a.akamaihd.net/ugc/1003681785838658978/8C8037DEFA27C7261B0D1107DEF5958D28FB6960) (probably outdated, press F2 ingame for new list)

![Image of Buybinds](https://steamuserimages-a.akamaihd.net/ugc/1003681785838659254/D5CB4E25DB9EBD6B670D97DD0B832B504EC8D5FA)

Installation
============
Some of the files may be in the "extra stuff" folder. Check there if you cant find something.



put launch commands into launchcommands, if you do not how to do this, ignore it.

put all the files except "c4.wav" here;

Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg

put "c4.wav" here;

Steam\steamapps\common\Counter-Strike Global Offensive\csgo\sound

when using config for first time be sure to write "exec yuki" in console. if any weirdness happens just write "ae" in console and it will reload the config which should fix it. VERY rarely you might be stuck in an attack animation, hold ALT and press P to fix. (mega rare)

quickrcon.cfg, lollollol.cfg, quick.cfg, dongle.cfg and zeus.cfg are not needed, add them if you feel they'll be of use to you.

quick.cfg = training config

quickrcon.cfg = rcon version of quick (for non-local servers)

lollollol.cfg = become the MLG pro you always knew you were

dongle.cfg = let yourself become juan with your deagle

zeus.cfg = let lightning rain from above

keyhelp.cfg - contains an ascii-image keymap for buybinds. strongly recommend you to download this to learn the buybinds.

Extras (Text Update)
============
This will update your text in game, mostly it makes things more easy to read, increases size and what not. This textfile contains some internal jokes in my friendgroup as well as modifying some text to be Swedish. I don't recommend using it unless you speak Swedish.

Put csgo_yuki.txt in your resource folder:
Steam\steamapps\common\Counter-Strike Global Offensive\csgo\resource

Add "-language yuki" to your launch options.

Extras (new menu background)
============
If you download the file "pf55menu.webm" you can change your menu background in counter-strike: global offensive. I recommend you make copies of the files you will replace in case you want to revert to the original menu appearance. In order to make this work you will need to replace files found here:

Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\panorama\videos

With the .webm in question. Rename the "pf55menu.webm" to match the name of the webm used as your menu background. Easiest way to see which one you are supposed to replace is by starting CS:GO and checking what video plays in the background. Find the corresponding video in your folder and copy it to create a backup. Now delete the original and rename "pf55menu.webm" to its file name.


For example if the menu background is sirocco_night.webm you will rename pf55menu.webm as "sirocco.night.webm" and replace it. You might have to do this for the 540p or 720p version if those are being used.

Usage
============
Press "F2" to see all non-default binds listed in console.
Press "PAGE DOWN" to see map over buybinds in console.

Helpful Info
============
This config supports multiple viewmodel settings and multiple crosshairs. If you use crosshair or viewmodel to line up grenades you can edit the toggles to have both your normal crosshair+viewmodel as well as a viewmodel/crosshair you use to line up your grenades.

The crosshair supports different color for different crosshairs without breaking the nadecolor-binds.

Thanks
============
Ideas/inspiration/co-operation


Maddada

TheElderNigs

KeGaMo
