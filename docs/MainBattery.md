---
category: basic-system
---

Main Battery
------------

This system represents a ship's principle offensive weaponry; the standard ship-to-ship weapons of whatever fiction the ship lives in. A single battery can represent several mounted barrels, emitters, or turrets working in tandem; or a single turreted weapon with one or more barrels/projectors. It is less effective at long range due to accuracy of firing solutions, spread of the individual projectiles/rays, etc.

Symbols:
![](assets/main-battery-class-2-fs-three-arc.svg)
![](assets/main-battery-class-3-fwd-arc.svg)
![](assets/main-battery-class-1-all-arc.svg)

Rolling To Hit
--------------

See [Range and Bearing](RangeAndBearing) for details on how to find direction and distance to targets.

To determine the effect of firing on a target, a number of dice are rolled depending on range. Class-3 batteries have a maximum range of 36&Prime;. When firing at a range of 0-12&Prime;, three dice are rolled; at 12-24&prime;, two dice; and at 24-36&Prime;, one die. The following table shows the number of dice to roll indexed by battery class and range to target.

|              | **0-12″**    | **12-24″**   | **24-36″**   | **36-48″**
| ------------ | :-------:    | :--------:   | :--------:   | :--------:
| **Class-1**  | **ONE** D6   | ---          | ---          | ---
| **Class-2**  | **TWO** D6   | **ONE** D6   | ---          | ---
| **Class-3**  | **THREE** D6 | **TWO** D6   | **ONE** D6   | ---
| **Class-4**  | **FOUR** D6  | **THREE** D6 | **TWO** D6   | **ONE** D6

Unscreened Damage
-----------------

Damage is dealt according to the results of the dice. The target ship must cross off a number of <span class='hull-boxes'>j</span>hull boxes according to the total damage points generated as detailed in this table.

| Every **1**, **2**, or **3** rolled | No effect
| Every **4** or **5** rolled         | **One** damage point
| Every **6** rolled                  | **Two** damage points

Damage Protected by Screens
---------------------------

Defensive [screens](ScreenGenerator) reduce the damage from beam batteries.

| **Level-1 Screens** | Rolls of **4** have no effect
| **Level-2 Screens** | Rolls of **6** inflict only **one point** of damage

Class-1 Point Defense Mode
--------------------------

Class-1 beam batteries can be fired in defense against approaching small craft and missiles. This requires the use of one [fire control](FireControlSystem) system, but this one can be shared among any number of Class-1 batteries being used in point defense mode.

1D6 is rolled as normal, but only one hit is scored on a roll of **5** or **6** (as if being affected by level-2 screens).

Design Procedure
----------------

| Battery       | Bearing          | Mass | Cost
| ------------- | ---------------- | :--: | ----
| _Class-1_
|               | 360&deg; (6-arc) | 1    | 3 points
| _Class-2_
|               | 120&deg; (3-arc) | 2    | 6 points
|               | 360&deg; (6-arc) | 3    | 9 points
| _Class-3_
|               |  60&deg; (1-arc) | 3    | 9 points
|               | 120&deg; (2-arc) | 4    | 12 points
|               | 180&deg; (3-arc) | 5    | 15 points
| _Class-4_
|               |  60&deg; (1-arc) | 5    | 15 points
|               | 120&deg; (2-arc) | 8    | 24 points

Lore
----

The nature of the main battery must conform with the basic rules: its a barrage of *something* that hits roughly 50% of the time, and damage can be reduced by defensive systems mounted on the target. This lends itself to the concept of _laser beams_, _phaser beams_, and _particle beams_, but it doesn't rule out _high-velocity projectiles_ or other _ballistic missiles_.

_Laser and Blaster Beams:_ Energy beams fired upon the target in volleys or a continuous beam over the course of a turn. Defensive systems are energy shields that absorb, deflect, or dissipate the incoming beams. The shields can be overloaded by especially direct shots allowing some damage through.

_Phaser and Particle Beams:_ Hyper-accelerated particles fired toward the target in volleys or beams. Defensive systems can be energy shields or magnetic fields that dissipate the incoming particles, lessening the chance of damage.

_High-velocity Projectiles and Ballistic Missiles:_ Gun barrels or launch tubes fire volleys of penetrating slugs or small rockets. Defensive systems are likely some form of active armor or laser-based point interceptors that physically deflect or vaporize some of the incoming weapons.

You can optionally rule that screen generators simply don't exist in your setting and require ships to use some kind of [ablative armor](AblativeArmor), or even trade standard batteries for ships with only [torpedo systems](TorpedoSystem) creating a different flavour of sci-fi.

External Links
--------------

[Main battery - Wikipedia](https://en.wikipedia.org/wiki/Main_battery)
