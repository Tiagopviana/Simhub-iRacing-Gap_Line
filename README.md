# Simhub iRacing Gap Line

**Simhub Overlay, for iRacing.**

<img src="images/Gap Line Logo.png" />

This overlay will show the cars ahead/behind, according to the distance to the player. And gives more information, like Offtrack/Blackflag/Meatballflag, sector line and cars in pitbox.

I will share 2 versions (lite and max) of the same idea. They work in different ways, but do the same function.

## Overall information:
The main function of this overlay is to help the player to take the right decision, if in front there is a slow car driving or an accident.
You can as well check if the gap to the surrounding cars is increasing or decreasing (no need to check the F3 box).
If you race multiclass races, it can be usefull to check for the incoming fast/slow class.


**Different examples GIF:**

<img src="images/tpv-gap line-101.gif" />

<img src="images/tpv-gap line-102.gif" />

<img src="images/tpv-gap line-103.gif" />

<img src="images/tpv-gap line-104.gif" />

As shown in the GIF animation, the suggested position of the graph should be around the rearview mirror. Far enough to not be a distraction, but close enough to give you the required information to avoid problems.

## Lite version
(needs this plugin: https://www.simhubdash.com/community-2/dashboard-templates/romainrobs-collection/):

This version uses the Romainrob iRacing plugin. And only shows 5 cars in front and 5 cars behind (total 10 + player). Will not give information if a car is in the pitlane/pitbox. Will not give sectors position and startline.
But will show the Offtrack/Blackflag/Meaballflag.

### Lite problem:
the major problem from this version (in relation to the max): Because only show 5 cars in front, if a bunch of cars gets involved in a big accident, the slow cars will pop up once they are the 5th or 4th, etc in front of you...
If you drive in a close group of 5/6 cars in front of you, you will not see the slow cars coming in the graph, only when is too late... The max version solves this problem!

I made this version, with the hope it will be lighter to run, in relation to the max version (I cannot prove, if it is a valid assumption).
If you have a weak computer, use this overlay, probably.

## Max version:
This version will show all cars, 64 if you race in a server with 64 drivers... So, starting line can be hard to manage... Test it!!!

## What should you use?
If you have a good PC, just use the max version. 

If you have a weak PC, try first the max version. If you race in a small group of cars(20), it should not be a problem. If you race multiclass and full grid (50), the starting of the race could be hard for the PC.

## Config the overlay:

### Draw Distance
You can change the draw distance in this file: \TpV-Gap Line Lite\JavascriptExtensions\tpv-gap line.js

<img src="images/tpv-gap line-007.png" />

for lite, the drawing distance is in seconds. **Defaut is 8s**

<img src="images/tpv-gap line-008.png" />

for max, the drawing distance is in meters. **Default is 300m**

### Overlay dimensions
If you need to change the dimension of the overlay, you need to match the width in pixel of the overlay with the pxwidth() found in the javascript folder. **Default is 1000px**

<img src="images/tpv-gap line-006.png" />

<img src="images/tpv-gap line-005.png" />

### NOTE
You can change the colors of the warning here too!

## Usage:
You are free to edit and add to your existing shared overlays. Just give a shoutout and point to the source! And share your improvements!

### Tiago Viana
you can find me in the Discord Simhub server! (tiagopviana)

