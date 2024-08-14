Paprika Mod
===========

Based on Captain Kwok's Balance mod.

Components:
- Added 290kT Tactical Spaceyard Component for Small Freighters
- Added Overdrive Thrusters for Ships at Contra-Terrene Level 1 for +1 combat movement (modified by hull size, below).
- Increased Ordnance consumption from 5 to 25 for nearly all Seekers. Not affected are Biological weapons and some Bombardment weapons.

Facilities:
- Added Highly Industrialized Slums and Legacy Infrastructure. Inspired by SuicideJunkie.

Combat Speed: Is now modified by hull size. All percentage values are compared to BMv125.

Warships get the following combat speed bonuses or penalties:
- Frigates                   +20%
- Destroyers                 +10%
- Light Cruisers               0%
- Cruisers                    -5%
- Battleships                -10%
- Dreadnoughts and Baseships -15%

Fighter and Drone speed AND maneuverability have been increased by 50%.

All relevant racial hulls were updated as well.

Freighters and Colony Ships and Carriers are unchanged at -25% speed and maneuverability.

Homeworlds:

Homeworlds are much stronger in Paprika than in Balance Mod. Most production and construction rates have been increased by around 60%.
Homeworlds receive special facilities that cost no maintenance, but they cannot be built by the player or AIs (subject to change). 
This places more emphasis on protecting and capturing homeworlds. Some common strategies for colony bombardment may be more difficult due to increased ordnance consumption.


Captain Kwok's Balance Mod for Space Empires V
==============================================


Contents:
---------

1.  Background
2.  Brief Summary of Changes
3.  Installation
4.  Important Notes
5.  Adding Custom Races to the Balance Mod
6.  Website and Contact Info
7.  Special Thanks


1. Background:
--------------

The original purpose of the Balance Mod was to supplant the default data files
that are included with Space Empires V with balanced files that retained the 
spirit of the standard game. A collection of SE:V beta testers participated in
its initial development and since then many others have provided comments and
suggestions that have shaped the mod into its current form. Hopefully the mod 
addresses most of the issues that take away from the standard SE:V game.


2. Brief Summary of Changes:
----------------------------

For the most part, the tech tree remains close to standard SE:V with most of the
changes confined to a reduction in the number of tech levels and where some of
branching occurs. Overall, research has been increased in cost to retain the
long length of the tech tree and to reduce the need to retrofit items frequently.

The mod incorporates parts of Fyron's Quadrant Mod, which adds a number of new
systems and quadrant types, and generally makes each system unique and interesting
to explore. A few other graphic changes were made, reducing the size of empire flags
without reducing the usefulness of the colony status bar.

Ship sizes have been slightly modified and there is a return to a SE:III
style propulsion system where larger ships require more engines to move. Ship
balance between small and large ships is improved as well as between units and
ships.

Components and facilities should be more balanced and a few additions were made to
help with ship designing. Costs are slightly more diversified and descriptions updated
to provide helpful ability or stacking information. Over the development of the
mod, a few components or facilities had been modified to provide a different ability
then they did in standard SE:V.

Weapons have also been adjusted to allow for a variety of research and
deployment options. Hopefully this should allow for a number of viable weapon
strategies that can work throughout the game. Weapon mounts now provide only
a modest bonus to damage and range in exchange for increased cost.

Resource extraction has been slightly diversified to make Organics/Radioactives
more important. Research has been spread out a bit more, which more significant gains 
per tech level. The intelligence system is now "leaky", which gives an opportunity 
for even a small empire to score the occassional project success.

There's also been tweaks to improve the fairness of racial traits and other
empire modifiers like government types or society types.

The AI has been extensively updated and developed. The AI is setup to utilize almost
any item that players can. The personalities of individual AIs are more readily apparent
AIs can offer a challenge to most players. Many of the ministers work well enough for human 
players to trust and handle some of the more mundane aspects of empire management.


3. Mod Installation:
--------------------

1.  Extract the contents of .zip/.rar file to SE:V's GameType folder (..Space Empires V\GameTypes)
2.  When starting a new game or using quick start, select "Balance Mod v#.##" from the list
    of game types to use the mod
3.  Enjoy!

Note that saved games with the mod will automatically load the mod when you load them.


4. Important Notes:
-------------------

1.  You cannot use saved maps, game setups, or empire files from the standard game with the Balance Mod.

2.  If you're making a few changes to the Balance Mod, consider the followng:
      - Modifying the ship sizes will likely cause issues with AI ship design since the AI uses specific hull
        sizes to determine the amount of space to dedicate to weapons or speciality components
      - The AI references many items by name, so changing names can cause issues
      - The impact of the above changes can be mitigated by making the appropriate adjustments in the Balance
        Mod's AI scripts. Source scripts are usually available for download from the Balance Mod website.

3.  The default AIs used for ministers are scripted to use certain weapons and armors, so they won't
    typically use racial trait items or necessarily the best weapon available.


5.  Adding Custom Races to the Mod:
-----------------------------------

If you've downloaded a new shipset and would like to use in the Balance Mod, follow the steps
below:

1.  Create a folder in the Balance Mod's Empires folder with the same name as the Race's default folder - it
    is important to use the exact same name so the game will now where the pictures and models are
2.  Copy the race's [Race Name]_AI_main.txt file into that folder
3.  Edit the following lines in [Race Name]_AI_main.txt:

    From:
    AI Script File                                := [Race Name]\[Race Name]_Main_Script.csf
    AI Script Empire Setup File                   := [Race Name]\[Race Name]_Setup_Script.csf

    To one of the following default scripts:
    AI Script File                                := Default\Default_Main_Script.csf
    AI Script Empire Setup File                   := Default\Default_Setup_Script.csf

    AI Script File                                := Default\Default_Defensive_Main_Script.csf
    AI Script Empire Setup File                   := Default\Default_Defensive_Setup_Script.csf

    AI Script File                                := Default\Default_Aggressive_Main_Script.csf
    AI Script Empire Setup File                   := Default\Default_Aggressive_Setup_Script.csf

This will tell the AI to use the Balance Mod's default AI files with the ship set, making sure it works
properly with the mod.


6.  Website and Contact Info:
-----------------------------

For updates, additional resources and information:
http://www.captainkwok.net/balancemod.php

Balance Mod Help Page:
http://wwww.captainkwok.net/balancemodhelp.php

Balance Mod FAQs:
http://www.captainkwok.net/balancemodfaqs.php

Balance Mod Minister FAQs:
http://www.captainkwok.net/balancemodministers.php

Balance Mod Discord Channel:
https://discord.gg/xPWVbX3WAX

Archived! Balance Mod Discussion Forum at Spaceempires.net:
http://www.spaceempires.net/home/forum-73.html

Comments/Questions:
http://www.captainkwok.net/contact.php


7.  Special Thanks:
-------------------

Nolan Kelly (Fyron)
  - Inclusion of FQM, generic slot layouts, testing and suggestions

Chris Traber (Tampa_Gamer)
  - Ship Experience values, testing and suggestions, Balance Mod tech chart

Nick Dumas (SuicideJunkie)
  - Suggestions, small main Empire flag sets

Jonathan Sorensen (se5a)
  - Small component images, testing and suggestions

Kwayne
  - Toltayan Ship Set adapted for Balance Mod

Andreas Brüngger (Q)
  - Testing and suggestions

Paulo Brito (CrazyDog)
  - Testing and suggestions

Baron Munchausen
  - Testing and suggetions

Philipp Kullmann (Mephisto)
  - Testing and suggetions

Bruno Ethier (Paladin)
  - Testing and suggetions

Wayne Witzke
  - Additional small size flag sets

Grendel, Albi_joe, Crissa, Ender, Prisoner881, Nikqz, gurachn, MysticVoid7x9, Zap etc.
  - For all their friendly and detailed posts/e-mails about items in the mod

Additional sound effects from https://www.zapsplat.com

Thanks to all those that volunteer at various times to beta test!

A special thanks to all the other posters at Shrapnel, SpaceEmpires.net, and SpaceEmpires5.com for their
feedback, AI script suggetions, and other comments!
