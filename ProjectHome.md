# OTL's tf2 Hud #

12/21/12 Working on hud updates. Update should be out soon to fix crashes. I wont be able to get the new weapons for a while though, so I can't fix those.
**I updated the Vaccinator, but I am unable to get the status icons to move properly. I am leaving them in place for now. More updates this week.**


11/29/12 I forgot to switch the default scoreboard to the higher res version. Having issues re-uploading right now. All scoreboards are in the addons folder though.

11/28/12 Hey Everyone! I finally got around to updating this. I am still abroad, but I couldn't stay away from tf2.

  * Tweaked Target ID Health text
  * Added options for Team Bordered Health cross, and no health cross
  * Fixed Koth timer issues
  * Fixed MvM bugs
  * Added a Larger Stick Meter for Demos
  * Fixed health status icons
  * Some compatibility for Koth\_lakeside\_event
  * etc.
Let me know if you find any bugs

8/29/12 I will be studying abroad this fall and not playing tf2. This hud will not be updated for the next few months. I do not think valve will release another major hud breaking update for a while because of MvM, so this should last a while. If you have any errors after a valve update try re-downloading and re-installing the hud. Sorry to the few people who follow this hud.


8/17/12 added MvM compatibility. Still might be some bugs, let me know!

I have not had time to fully update this for the Pyromania Update.
I have added Sniper Focus, but as of yet do not have all the new weapons. I also have not been able to test the new game mode sd

## Latest Changes ##

7/4/12
I have added an addons folder. Now if you want to change your scoreboard or damage color, etc. you only have to drag and drop the appropriate files!
Also I made the control point icons larger on Minmode 0 (minmode off).

## General information ##

---

A modification of the basic tf2 hud.

inspired by garm3n, eve, toasty, broesel, m0re, pvhud, and many more.

(06.06.2012) Version 0.7.1 has been released.


---


To install:
Go to:

Steam>steamapps>"account name">team fortress 2>tf

and remove your old resource folder (scripts too, if you have one). Save these incase you want to reinstall your old hud later.

Then move the resource and scripts folders (provided from this hud download) to the tf folder.

Use the Addons&Extra's Folder if you want any of the changes for Scoreboard, Health Color, Damage COlor, sticky # positioning, & target ID change.
(just drag and drop to the appropriate folders)


---

If you would like to see the hud, please view the ScreenShots page.

---

## Credit ##
  1. I would like to note that the MainMenu was taken from Sinder's e.v.e. hud. I made some slight modifications with implementation of Minmode buttons, but it largely was his file.
  1. I also began this hud with garm3n tanlight. While I restarted the hud using the tf2 directory files, a lot of the hud remains tied to garm3n. I am still in the process of completely purifying the files.
  1. I'm not sure if I would call this a custom-made hud. It's more of OTL's compilations.

---

## Features ##
There are two working modes switchable with cl\_hud\_minmode 0/1. Both designed for normal or 6v6 play. Visit the ScreenShots page to see.
Contact:
usererror413@gmail.com
http://steamcommunity.com/id/UserErrOr413/


---


### HudCrossHairs ###

I have installed several hud crosshairs. They are installed in:

scripts>"HudLayout.res"
In the sections labeled "Garm3n Crosshairs" and "Fog's Crosshairs"

Activate the crosshair by going to your scripts folder and then hudlayout.
Change "visible" from 0 to 1.
Change "visible\_minmode" from 0 to 1.
Change "enabled" from 0 to 1.


If the crosshair isn’t centralized do the following:

1. Go to your scripts folder and then hudlayout.
2. Change the xpos and ypos values. (xpos is for horizontal and ypos is for vertical).
3. Save and "hud\_reloadscheme"
4. If not, Alt+TAB and try another value and save.
5. Go back into the game and type hud\_reloadscheme in console.
6. Do this until you’re happy.

(If the crosshairs isn’t centralized [a pixel or two](by.md) then you sometimes have to change “wide” and “tall” too, not just “xpos” and “ypos”)

If you want to change the colour go to your scripts folder and then hudlayout.
Change the fgcolor to the colour you want.

For example,
bright-white:	"255 255 255 255"
green:		"0 255 0 255"


---


### Scoreboards ###

Default scoreboard is 6v6 only, formatted for xxxx by 1280.

If you want a 12v12 scoreboard;

resource>UI
rename: "scoreboard1280\_12v12" to "scoreboard"

--

If you use a lower res and the scoreboard does not fit;

resource>UI
rename: "scoreboard800\_6v6" to "scoreboard"

--

If you use a lower res and want a 12v12 scoreboard;

resource>UI
rename: "scoreboard800\_12v12" to "scoreboard"

--


---


### Health color ###

The default player health is green. As seen in ScreenShots

If you prefer white as your default health color;

resource>UI
rename: "HudPlayerHealth\_white" to "Hudplayerhealth"

and

scripts>
rename: "hudanimation\_tf\_whitehealth" to "hudanimations\_tf"


---


