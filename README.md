# Playable Rebel Flagships

This mod includes a set of playable flagships.

The goal of this mod is not to build a balanced ship, but instead to allow the player to have the experience of flying the rebel flagship through space.

While the rebel flagship cannot be reproduced 100% faithfully to the original ship, this mod attempts to provide as authentic a ship as possible. It will hopfully offer a fun and enjoyable play experience.

## What you need

In order to play this mod, you'll need a mod loader for FTL.

These mods have been tested with the [Slipstream Mod Manager](http://www.ftlgame.com/forum/viewtopic.php?t=17102)

## How to use the mods

Place the contents of the `mods` directory into the Slipstream `mods` folder. Launch Slipstream, and select the ships you'd like to play.

## How to use the .sav files

Copy an included save file to your save games directory, and rename it to `continue.sav`. Make sure the appropriate ship mod is loaded before continuing the game, otherwise FTL is likely to crash.

Save games location depend on your platform and game source.

* OSX: `Library/Application Support/FasterThanLight/` in your home directory.
* Windows: `My Documents\My Games\Faster Than Light` in your home directory.
* Linux: `.local/share/FasterThanLight/` in your home directory.

## Playing with this mod

FTL has a few limitations relating to high reactor levels and multiple artillery cannons. Most of these issues have workarounds, discussed below.

* The player can only control the power level of the 1st artillery cannon (the Boss laser)
    * Zoltans can be used to add power
    * Hacking the save games can be used to add power
* The cannon upgrades apply to the last artillery cannon (Ion, Beam, or Missile depending on variant)
    * Weapons mods can be used to avoid the need to upgrade the cannon
    * The included ships include appropriate upgrades for each Phase.
* All cannons start the game with 1 bar of power allocated.
    * Zoltans can be used to add power
    * Hacking the save games can be used to add power
* Nebula storms cause FTL to crash for ships with more than 30 reactor units.
    * Limit ships to 30 rector units, or avoid nebula storms.
* Battery power counts against the nebula storm limit.
    * Do not use the battery in a storm.
* Nebula storms can rob power from the artillery cannons.
    * Free up power from other systems before jumping into a storm.
* Cannon power lost to damage or Ion will be recovered, only if it not allocated elsewhere.
    * Ensure that reactor power is always available for the artillery.
* Crew position is iffy when moved by hacking a save file.
    * Move crew to normalize their position if they fail to repair a system.

## Play hints

### Be cautious of losing cannon power

Certain conditions can cause power to be lost from the artillery cannons. In some conditions, this power will not automatically be restored. While you can add power to Artillery 1 using the GUI or `y` hotkey, the only way to add power to the other cannons is to hack your save game (using a hex editor), or walk a Zoltan in and out of the room (only possible/useful for missile artillery.)

Be aware of situations that can cause power loss, and attempt to avoid them.

### Avoid nebula storms

Nebula storms cut available power in half. If more than half the reactor power is allocated to systems, it will be robbed from the systems as required to cut allocation to this 50% mark.

Unlike ion buildup and system damage, power removed this way will not be restored to systems after exiting the storms.

The best way to address this problem is to avoid storms completely. However, if you must jump through a nebula storm, you should remove sufficient power from engines, shields, and other systems to ensure that no power is removed from the artillery cannons.

Advanced sensors are included allowing you to pilot around storms.

Be aware that storms are often present when diving into the rebel fleet. Advanced sensors will not warn these storms. I recommend avoiding storm diving, but if it is unavoidable, be sure to reduce system power before each jump to avoid robbing power from your cannons.

### Avoid re-allocating cannon power

If the artillery cannons are hit with Ion or damaged, power will be restored to the system once de-ionized or repaired. If either of these events happen, be sure that you do not allocate the cannon's power elsewhere; if you have no spare power bars, cannon power will not be restored.

Be cautious about this when using the battery; systems powered by the battery will switch to spare reactor power when the battery is drained. If this happens, you may not have available power for the cannons when the come back online.

### Avoid using the battery in storms

Battery use in storms will bump the power above 30, causing the game to crash. If this happens, simply restart FTL, and avoid using the battery.

### Reposition the Artillery crew

The included save games have been manually hacked to place crew in the axillury cannon rooms. In some cases, the crew might not repond to system damage. If this happens, attempt to move the crew, and they should begin repairs.

### Other crashes

Obtaining a boarding drone in an event caused the game to crash during play testing. I believe the issue has been addressed, but if it happens, restart FTL and avoid that beacon. If the beacon is unavoidable, allow the Rebel fleet to reach the becon, and dive the fleet.

## What's included?

This package contains 4 playable ships, a set of modded boss weapons, and save files hacked to provide an optimal play experience. All the original systems are included on these ships, and you may add additional subsystems such as batteries and sensors by purchasing them at stores.

Boss0 may be customized with your preferred special systems. All other variants must be run with the supplied special systems.

### Boss0

![Boss0](http://i.imgur.com/Vrjvf0I.png)

Boss 0 replaces the Kestrel Cruiser, variant A. It provides a user playable flagship that requires no hacks or other consessions to use. The Rebel Flagships artillery cannons are mounted as conventional weapons.

A goal of this variant is to require no hacks to play. It has no known UI issues, and can be run from a conventional new-game.

This ship includes a custom set of Boss weapons; these weapons take 2 power to run, and have been modified to have the same cooldown time as the Level 3 Boss Artillery cannons.

This ship starts with minimal stats. All systems are available to purchase at shops, and additional firepower can be unlocked by adding power to the weapons system. This variant does not include the boss drones, and supports only 3 drone slots to avoid UI issues.

This ship has 30 hull points, unlike the other variants.

### Boss1

![Boss1](http://i.imgur.com/7TT8bL5.jpg)

Boss1 replaces the Federation Cruiser, variant A. This ship replicates the rebel Flagship, Phase 1.

This ship is limited to 30 power bars, plus power from Zoltan and batteries. See the notes above for additional information about power management. The original ship includes 42 reactor units.

This ship has only 20 points of hull, in keeping with the original flagship specifications.

Advanced Sensors are included in order to allow the player to deal with Nebula Storms.

I recommend using this ship with `continue.p1.norm.sav` or `continue.p1.hard.sav`. The save files place crew members in the annex artilery rooms, and set Artillery to power level 3. Without the save, you will not be able to power additional artillery, or repair damaged cannons.

### Boss2

![Boss2](http://i.imgur.com/G20MdVV.jpg)

Boss2 replaces the Federation Cruiser, variant B. It replicates the rebel Flagship, Phase 2.

Because this boss has Artillery, drones, and no weapons, there is a UI issue where the artillery and drone system power overlap. In practice, this should not create any problems. You can use the `y` hotkey to manage artillery power, and the drone UI elements/hotkeys to manage drone system power.

This ship is limited to 30 power bars, plus power from Zoltan and batteries. See the notes above for additional information about power management. The original ship includes 44 reactor units.

This ship has 22 points of hull armor.

The drone surge is not supported, however the ship includes all Boss specific drones, including the boss defense drone, and boss boarding drone.

Staying faithful to the original Rebel Flagship, this variant starts with only 10 drones. I recommend using drones sparingly in the early game.

Advanced Sensors are included in order to allow the player to deal with Nebula Storms.

I recommend using this ship with `continue.p2.norm.sav` or `continue.p2.hard.sav`. The save files place crew members in the annex artilery room, and set Artillery to power level 3. Without the save, you will not be able to power additional artillery, or repair damaged cannons.

### Boss3

![Boss3](http://i.imgur.com/nhGSf52.jpg)

Boss3 replaces the Federation Cruiser, variant C. It replicates the rebel Flagship, Phase 3.

This ship is limited to 32 power bars, plus power from Zoltan and batteries. See the notes above for additional information about power management. The original ship includes 44 reactor units.

This ship has 20 points of hull armor.

The boss Power surge is not supported at this time, however if there is interest, weapons mods could be included to replicate both the laser surge, and possibly a drone mod to emulate the Zoltan shield recharge.

This Flagship variant includes a Zoltan shield, however unlike the original Flagship Phase 3 encounter, the player shield only has the normal 5 bars of power. Advanced Sensors are included in order to allow the player to deal with Nebula Storms. See notes.

I recommend using this ship with `continue.p3.norm.sav` or `continue.p3.hard.sav`. The save files set Artillery to power level 4. Without the save, you can only power up the Missile artillery using a Zoltan crew member (not included.)

## Hints (spoilers)

Half the fun of FTL is learning strategies. This section may spoil the experience for you.

### All ships

* Try to obtain Engi med-bot dispersal or a clone bay early.
* Clone bays and Engi med-bot dispersal can heal crew in your annex artillery rooms.
* Keep scrap handy for critical upgrades.
* Top off the armor; you only have ~20 points to work with.
* An emergency jump with the clone bay can heal and save your crew.
* Turn off o2 to kill enemy boarders trapped in the Annex artillery rooms.
* Spend money on alien crew members. Zoltan, Engi, Rock, and other aliens will give you an edge.
* Zoltan crew membes can add power to artillery, and help address power shortages in the later game.
* Surviving the boss battle usually comes down to upgrading your engines and finding the right Augmentations.
* O2 upgrades can save your artillery crew in the event of a breach.

### Boss0

* This ship is OP. You don't need hints.

### Boss1

* Save the cloak to avoid missile that might hit your artillery rooms.
* Use Hacking to return enemy boarders to their ship if they happen to board your artillery rooms.
* Upgrade your engines ASAP. This ship is unlikely to survive the final encounter without high level engines (E.g. Lvl8)

### Boss2

* Artillery alone will carry you through the first half of the game.
* Save your drones until you find a drone recovery arm.
* Do spend drones on missile defense; a strike to an artillery room can kill your crew and take the system offline perminently.
* Consider replacing the beam drone. A second (or third) laser drone will help keep shields down for your artillery in later sectors.
* Save for a hull repair drone; it provides a massive edge between boss battles.

### Boss3

* Obtain a clone bay ASAP; your artillery will frequently kill your boarding crew.
* Avoid boarding until you have a clone bay.
* Use mind control against enemies that attempt to board your artillery rooms.
* Don't worry if your artillery crew are mind controlled. They are perfectly capable of repairing any damage they cause.
* The best defense is a good offense. Boarding the enemy ship can prevent them from boarding you.

