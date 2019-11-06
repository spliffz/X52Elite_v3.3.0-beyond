This is an update on the Saitek x52 Profile for Elite Dangerous originally made by /u/GangreneTVP.
I used the profile myself for years now, but since I started playing Elite after the Beyond Update I decided to update it.
That means that the new Full Spectrum Scanner and other new features like the Camera Suit are now included.


I tried to keep the existing binds as much as possible but ended up redoing the following buttons:
For main flight I reassigned the "Hyperspace" and "toggle orbit lines" buttons.
This makes making use of the new scanner possible, as it needed it's own button.
I never used the "Hyperspace" button since it's just a FSD toggle. And orbit lines you can easily toggle on the right panel now.
Inside the scanner everything works separately.

Since accessing the camera suite was already bound I added the movement.
The on-screen controls might be a bit confusing, so be sure to check the reference pictures.

This profile is also VR/Headtracker & VoiceAttack/HCSVoicePacks ready!


[How to use]

Extract the .zip and put the extracted files into the following directories:

Put the Elite Bindings .binds into the elite keybinds folder:
C:\Users\<yourusername>\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings

Put the Logitech Profile .pr0 into the Logitech x52 folder.
C:\Users\Public\Documents\Logitech\X52

In the Logitech X52 software load the "X52EDV330BR1.pr0" or "X52EDV330BR1Pro.pr0" and click the "profile" button to load in onto the X52.
In Elite change the control preset to "X52Elite v3.3.0-beyond-r1".


Enjoy!


The profile is made with the Logitech software for the X52.
Version 8.0.134.0.

I don't know if this works on older versions of the software, or the Saitek software.
I use a Saitek X52 with the Logitech Software and so far it does what it needs to.


--------------------------------------------------------------

[Changelog]
  [Nov 2019]
    - Made separate profiles for the X52 and the X52 Pro - Thanks to CMDR Sruliko for helping out with the X52Pro Profile!
    - Updated Logitech Software to 8.0.213.0 (Latest)
    - Renamed the profiles to something shorter so it doesn't crash the HOTAS.
    - Better reference pictures!
    [Changes Elite Bindings]
    - changed mic settings to Push-To-Talk
    - added button for selecting current system in gal map
    [Changes X52 Bindings Profile]
        - [Landing] Changed "Toggle Headlook" Button. This works also when you switch back to Flight mode. Recenter works fine.
        - Deleted unused buttons from profiler
      [SRV]
        - Moved the Handbrake to Pinkie + Secondary Fire
        - "Next Fire Group" and "Prev Fire Group" are now the same as your ship controls.
        - Added/fixed Galmap movement support

--------------------------------------------------------------

[Q&A]
Q: My LEDs on the stick are blinking and it recalibrates with a profile loaded:
A: If you have this specific issue, try renaming your Logitech X52 profile to something that is 16 characters or shorter. This is without the .pr0. It is 20 chars with the .pr0.
    Don't just copy/paste it! Open it up in the software and do a "Save As". As always, make sure you clear out the current used profile before you load the new one and load it up.
Q: How come sometimes I have button ghosting?
A: Make sure you clear out the current profile if you load up another.
Q: I have a X52Pro but the Elite Bindings File is not being recognized!
A: There is a small difference between Logitech and Saitek Controllers. Easy way is to open up any other .binds file you have in notepad/text editor and look for "	<Binding Device="X52Pro" ". Change that to what the other bindings file tells you.
    For the Saitek X52 it is "SaitekX52", For the Saitek X52 Pro it is "X52Pro", This could be different on a Logitech Version.


o7 - CMDR Spliffz
