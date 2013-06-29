CreativeProgrammingForDigitalMediaAndMobileApp
==============================================

Assignments for Creative Programming for Digital Media and Mobile App course at Coursera.org


 Title:   Project description for Peer Assessment Assignment 1
Credits:
Processing 2.xx IDE and tools:  The MIT License (MIT) - See Licence.txt for details

Template for this project offered by:   
Copyright (c) 2013 Mick Grierson, Matthew Yee-King, Marco Gillies
(University of London, International Programmes. )

Art assets (nebula, planets, debris,.... ) were created by Kim Lathrop

 App Tittle:   "Worlds at Peace and War"
 Author of App:   HoePhuan Ng, avtinc2000@gmail.com, Colorado, USA.
 Date:  6/29/2012

 Purpose:    
School :  Coursera.org, 
Course: 	Creative Programming for Digital Media & Mobile Apps 

Peer Assessment Assignment 1 -Creative Programming for Digital Media & Mobile Apps
Note:  This "Worlds at Peace and War" app is working 100% on my Windows 7 desktop.
  It does not work ( as javascript port)  on Chrome browser using Processing 2.xx IDE.
I have not tested it in Android either.
Seems like there are compatibility issues when porting from Java in Processing to others.
My Android phone when attached to my laptop seem to cause problems on my laptop,
when running past app samples for the class.
If you want to run it on Android ( since we are porting from desktop java to Android java), 
it should generally work, paste this code into an Android Processing template.

If you are my peer reviewers, and have problems with operation of this work, contact me at 
above email address.

This project is also a partial port (plus additions to meet this class's assignment requirements) of my python class work offered by Rice University at Coursera.org.  It is called "An Introduction to Interactive Programming in Python".

Note:  I did not spend time cleaning up this code since this is just hobby work.  
Already spent too much time with  bugs on Processing2.x.  Sorry.  may be this will be one of two parts.  I may be able to add more features to this in our coming  last assignment project #2.

Assignment solution:

Assets used:
Images:  nebula_blue.png, explosion_alpha.png, debris2_blue.png, asteroid_blue.png

All resources, images, screen shots, screencast are in sketch's data folder.   Some of the included resources were not used.

[The 3 files below are too big, as in 3.x gigabytes, so upload it a huge problem. ]
Following are in sketch 's data folder also.  They are demo submission to show functionality.
ScreenShotOfWorldsAtWarAndPeace1-PeaceMode.png
ScreenShotOfWorldsAtWarAndPeace1-WarAndChaosMode.png
ScreencastOfWorldsAtWarAndPeace1avi   ( video :   http://youtu.be/65rZ4-FOKJI )

Audio files:
BABYCRY2.WAV,
babygiggles.wav ( this does not work, even though it works on many other audio players.)
Bombaway.wav
explode.wav
female_scream.wav
mykbeat.wav  ( This is used for Peace mode )
etc.

Features:
Mouse slide / drag controls the following: 
-speed of planet / asteroids rotation.
-speed of debris in the universe
-speed of all audio

Buttons:
-”Peace” button:  	Puts the app into peace mode ( more on this later )
-”War and Chaos” button:  	Puts the app into peace mode ( more on this later )

Application operations:

a) "Worlds at Peace and War:  Worlds are at Peace!" mode:
When app starts up, it is in "Worlds at Peace and War:  Worlds are at Peace!" mode as show by its title 
at top of the app.  You can also go into this mode when you click the GREEN “Peace” button at bottom left corner.

In this mode, it shows a peaceful universe of many worlds where planets, asteroids, debris, all coexists.  Then music plays in the background.

User can slide mouse along x-axis (left-right) to decrease or increase speed of various artifacts.

b) "Worlds at Peace and War:  Worlds are now at War and Chaos!" mode:
When use click the “War and Chaos” red button at lower right corner, the app starts audio of screams, explosions, bombings, baby crying, and also sequence of random explosions in that universe.
Some sounds were suppressed when more than one were playing, as you will notice in this app.

I did not use image sequencing as presented by the professors.  Instead I used sprite images ( image sheet with sequential subimages) as well as other single (non-sprite) images.

Here is how I used the images and how they operate in this app:

Images: 
 nebula_blue.png: 	 This is the static image of that universe.

 debris2_blue.png:  
This is the scrolling image from left to right.  It makes the universe feels like it is moving!
Dragging the mouse from left to right will increase universe's motion and vice-versa!

explosion_alpha.png:  	
This is the sprite image of explosions.  It has 24 contiguous sprite sub-images.

asteroid_blue.png:  	This is the planet / asteroid images where I move and rotate them randomly.


Bug issues:

I have not figure out why some audio files work in many other audio players, but not with those in Processing 2.x.  I also notice when using larger audio files, Maxim (java audio wrapper class from this course) does not work!
If you know why, please inform.


Thanks.
HoePhuan Ng
avtinc2000@gmail.com
Colorado, USA. 
