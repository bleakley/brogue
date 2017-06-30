## Brogue+ v1.7.4.1

Brogue+ is not intended to take Brogue in a more Nethacky direction; it just offers a few new features that I think fit well within Brogue's already very elegant systems.

#### New Content

  * New monsters: goblin skirmisher and dar assassin
  * New boss monster: medusa (with her own special lair)
  * New legendary ally: valkyrie
  * New items: ring of spell chaining and wand of fortifications
  * New runics: weapon of enervation and armor of vanishing		

#### How to Download and Play

Windows-only executables are [available under releases](https://github.com/bleakley/brogue/releases). ASCII and tiles versions are both available.

#### Gameplay Changes

  * Lightning interacts with water in new ways.  If a bolt of lightning hits a (non-flying) creature in water the bolt will not continue in a straight line.  It will instead arc to the nearest creature in the water that has not already been hit by the bolt, or terminate if no such creature exists.  Also, a bolt of lightning will effect a submerged creature, but only in water (not a bog or lava). If the caster is standing in the pool of water he can be targeted by the bolt.  Water overrides any effect of a ring of spell chaining.
  * Medusa petrifies *everyone*.  If you think she has sealed you off from the rest of the level don't despair because her victims will eventually crumble away.
  * Rest and search have been unified.
  * Goblins, dar and ogres will enter a corridor when attacked at range.
  * Obstruction crystals extinguish fires.
  * Armor of respiration now has a timer (dependent on enchantment) that will expire if you remain in toxic gas for too long.
  * Imps and monkeys sometimes throw cursed potions.
  * 40% of all cursed runics have positive enchantment, some have very high enchantment.
  * Captive naga and trolls are less common and are found at deeper depths.
  * Whips worsen your stealth radius when you attack. (They are loud!)
  * Empowerment now cures discord and 'reloads' skirmishers with ammo.
  * Kraken now attack all adjacent enemies.
  * Spiders do more damage.
  * Pheonix eggs have much less health but regenerate quickly.
  * Pheonix and ifrit are classified as fireborne.
  * Acid turret classified as turret.
  * Black jelly, pink jelly, acid jelly and acid mound classified as ooze.

#### UI Changes & Bug Fixes

  * Monsters with items have an item icon on the sidebar.
  * A monster's combat info now correctly states the percent of health that will be poisoned by successive attacks with a staff of poison.
  * If two rings of the same type are equipped, the rings' descriptions will change to reflect the combined benefit.
  * High score list now reads "Killed by the Warden of Yendor".
  * Autopilot now ends if an item is stolen from you or if you pass a health alert threshold.

#### Credits
Thanks to Pender for making this wonderful game, thanks to andrewdoull and Guitar (from the old Brogue forums) for their ideas for the wand of fortifications and the medusa.

#### Known Issues
Very rarely, a medusa doesn't seem to petrify anyone (including the player).  This bug is hard to repeat and I don't know the cause.

#### FEEDBACK
I am looking for feedback, especially regarding:
Does the ring of spell chaining scale well with further enchantment?
Does the medusa petrify too quickly or too slowly?
Is the valkyrie too good for a legendary ally?  She never flees from combat and reflects healing and empowerment.  This is to intentionally make her harder to keep alive, which should offset her power.
