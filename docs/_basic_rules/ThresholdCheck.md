---
---

Threshold Check
---------------

When a ship looses an entire row of hull boxes, it can suffer damage to internal systems determined by a process called Threshold Point Check. The player of the ship rolls a six-sided die for each and every ship system considered vulnerable to threshold damage. The result of the roll depends on how many threshold points have been reached.

| Hull boxes lost | System destroyed on a roll of...
| First row       | 6
| Second row      | 5-6
| Third row       | 4-6

### Systems Vulnerable to Threshold Point Checks

Every system on a ship diagram are vulnerable to threshold damage except when noted. During a threshold point check, every vulnerable system is rolled for individually, 

__Normal Space Drive:__ The ship's [main drive](NormalSpaceDrive) is rolled for _once_ at every threshold check, but it takes _two_ failures to fully knock it out. The first time it is "destroyed", its thrust rating is reduced to half its full capacity. The second time it is destroyed, it is fully knocked out and provides 0 thrust./

__Screen Generators:__ While [defensive screen](ScreenGenerator) generators combine to produce a total level of screen, they are still rolled for individually at a threshold point check. E.g. a ship with __three__ generators rolls for each of them at the first threshold point and one of them is destroyed; effective defense remains at Level-2 since there are still two operational generators. At the second threshold point, the two remaining generators BOTH get destroyed---the unlucky player rolled two sixes in a row on the check---and defense is reduced to Level-0.

__Fighter Groups:__ [Fighter groups](FighterGroup) are rolled for individually but the icon represents each group's hangar bay. If it is destroyed with fighters still embarked, but the bay and the fighters are lost. If it is destroyed while empty i.e. the fighters in it had already been launched, then the ship simply cannot land six of its fighters. Returning fighter groups can sort into any still-operational hangar bays, or failing that their pilots can return via escape pod but any craft in excess of overall hangar capacity can no longer be fielded.

__Hangar Bays:__ General-purpose [hangar bays](HangarBay) are rolled for and destroyed just like fighter groups. Any ships embarked within a destroyed bay are lost, and any still in flight must be recovered by remaining hangar bay capacity if available.

__Cargo Space:__ [Hold and passenger space](CargoSpace) are NOT rolled for at threshold point checks. These systems are lost automatically when the end of each row of hull boxes are lost, so a ship's remaining cargo or passenger capacity is always proportional to its remaining hull boxes. This includes FTL towing capacity.

Internal Vs. Surface Damage
---------------------------

Systems knocked-out by [needle system](NeedleSystem) attacks are considered to have been destroyed by damage to the _surface_ of the hull, e.g. a battery knocked-out by a needle strike has had all of its barrels, turrets, or emitters busted up by precision hits. Systems knocked out by threshold points, however, are considered to have suffered damage to _internal_ mechanisms like magazine feeds, power couplings, sensors, and servos. This kind of damage is possible to repair or bypass which can be accomplished by [damage control](DamageControl).
