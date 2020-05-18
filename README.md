# TheatricalPrevisContest
http://www.mikewoodld.com/contest

Please note: the Windows version of the Capture Presentation File will be posted ASAP - probably within 24 hours. My apologies, there was a last minute problem and I'm working to get it resolved. The MacOS version is available now.

On Monday, May 18th, I'll be going live on YouTube at 1:00pm EDT to do a walkthrough of the Capture file, explaining how the DMX-controlled scenery and masking works, and answering any questions that you might have. That video will be available within a couple hours of the live stream. www.youtube.com/mikewoodld.

Please see the FAQ on the contest website.

<h2>Introduction</h2>

On this page, you'll find everything that you need to get started on your contest entry. The actual visualizer file is contained in the .zip folder. Be sure to choose either MacOS or PC as these files are not cross-platform compatible.

This file is a Capture Presentation file, which you can run without a Capture license. For the purposes of simplicity, from now on I will refer to this as just the "Capture file."

Navigating around in the Capture file is pretty easy. If you ever find yourself in a weird view, you can click on the settings icon in the bottom right corner to switch to a default camera view. Camera positions 1-3 have been stored for you already.

You can also switch between live view, wireframe view, plot view, and polygon view - I recommend checking these out and zooming/orbiting around a bit to get used to the rig and the theatrical space. Thanks to ETC for the theatre itself - you might recognize it from the ETC Training Files!

<h2>Patching Your Show</h2>

In the documentation, you'll find XLSX, CSV, and LW6 versions of the patch information. These are all identical - you can choose which one you need. <b>The channel numbers contained herein are merely suggestions</b> - you can patch anything to any channel you want. You cannot, however, change modes or addresses.

<h3>Patching Scenery & People</h3>

In the repo, you'll find an .xlsx file called "DMX Automation Information" - this document contains a list of all of the various things that you can control with DMX. There are people, vehicles, tables, chairs, pianos, a car, and even a bus! There are portal arches, foliage borders, trees, and more.

You can pick and choose which of these items you'd like to have in your show. If you don't patch them, they'll just stay hidden away offscreen. 

There are 16 actors available for your show. You can place them anywhere in XYZ space onstage. They originate 4 per corner and they have various poses. 

My favorite feature available to you is the modular stage decking. There are 20 deck sections, 4 deep by 5 wide, that you can conrol with DMX. You can use them to make all kinds of staging options. 

There are also two scenic portals that can be overhauled through the deck to change their opening. Just don't tell the carpenters. 

<b>You can control the hazer with DMX address 6/512.</b>

Finally, you are able to change the masking using DMX. You can fly a main curtain, midstage black, upstage black, and cyclorama. The legs can be flown out and the borders can change trims to reveal your electrics. When you fly the CYC out, you just might find a beautiful brick wall background... RENT, anyone?

<h3>Patching the Camera<h3>
  
So this is not necessary, but you're able to patch the Capture Camera to be able to control it through DMX. In the repo, there's a .esf containing a single instrument and three presets for it. You can advanced merge these into your show and move the camera around during your song using DMX.

The controls for the camera can be sensitive. I recommend opening the demo show file and messing with them a little bit to get a sense of what does what. 

    BkGndLev - Ambient Light Adjustment
    Background Level 2 - Exposure Adjustment
    Pan - Pan Left/Right
    Tilt - Tilt Up/Down
    Pitch - Roll
    TrckOffX - Truck L/R
    TrckOffY - Dolly US/DS
    TrckOffZ - Zoom
    Fog - IGNORE - Haze for this project can be controlled on Address 6/512.
    Layer - IGNORE
    Scene - IGNORE
    
You can override the DMX Camera controls at anytime by changing the view manually or by selecting a default view within Capture. Note that if you then change any of the DMX Camera Levels, the camera will snap back to the DMX position. Think of it as an LTP Camera Controller.

<h3>Selectively Patching</h3>
Depending on what hardware you have available to program with, you might want to pick and choose what things to patch in order to save on patched address counts. You can do this with fixtures, with people, with scenery, really anything. Just take some time to think about what you want to accomplish and choose the tools available that will help you make that happen.

<h2>Rig Notes</h2>
All of the fixtures are patched in the smallest modes possible to help conserve output counts. 

Some of the fixture placements - like the 2nd electric having the MLs and the CS Pars aligned like that, wouldn't fit in real life. But this is just fantasy. 

Some objects, mostly positions and architecture, have had some settings adjusted to not cast shadows in order to save on some rendering power.

When you zoom around in wireframe view, you'll see lots of pink lines. These are automation ranges for the various DMX automations. You'll also see lots of offstage scenery. The scenery lives offstage unless you patch it and turn it on. 

<h2>Programming Tips</h2>
If you want to have moving people or scenery in your song, put your moving people and scenery into their own cuelists and trigger them from your main list. Trust me, this will make your life a million times easier. 

You're welcome to use timecode or anything that will help you accomplish your goal.

The scoring rubric will be posted here very soon, but one of the points will be physics and how realistic your song is to accomplish. If all 16 people magically start flying at warp speed... well, no.

<h2>Wrap-Up</h2>
I'll be updating this readme throughout the process as more information becomes available or things change. Please make sure to check www.mikewoodld.com/contest reguarly. 

-@mikewoodld
  

