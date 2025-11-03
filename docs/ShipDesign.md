Ship Design Rules
-----------------

To start designing a ship, pick a hull size between 2 and 100. This determines the ship's overall mass and space available for fitting systems. The table below is a rough guide to the general size of certain ships. For example, lets design a ["survey cruiser"](CuriousClassSurveyCruiser) of mass 48.

| Ship Type | Hull Size
| --------- | ---------
| Courier   | 2-20
| Cruiser   | 20-50
| Freighter | 40-60
| Tanker    | 60-100

The ship's [hull integrity](HullIntegrity) is the number of hull boxes or "hit points" it has. An average ship has 25% of its mass in hull integrity, while a military ship gets 50%. Our survey cruiser has 12 hull boxes.

Most ships will need a [normal space drive](NormalSpaceDrive) and a [faster-than-light](FasterThanLightDrive) drive system. You are required to have at least one [fire control system](FireControlSystem), which is part of the ship's on-board computer and sensor systems. Our survey cruiser has a main drive rated Thrust-4, a faster-than-light drive, and one fire control system.

All of the ship systems so far, as well as the structure of the ship, fuel tanks, crew accomodations, etc. take up 50% of the mass available, leaving the other 50% for you to fit additional systems as desired. The survey cruiser has 24 mass available, and as a research ship let's reserve 15 of that for [science facilities](CargoSpace#science). The remaining 9 mass is enough room to mount a superior sensor platform (mass 2), a [defensive screen](ScreenGenerator) generator (mass 3), two [point defense](PointDefenseSystem) systems (mass 2), and two Class-1 [batteries](MainBattery) (mass 2).

Civilian Systems
----------------

* [Cargo Space](CargoSpace)
* [Damage Control](DamageControl)
* [Faster-Than-Light (FTL) System](FasterThanLightDrive)
* [Fire Control (FireCon) System](FireControlSystem)
* [Hangar Bay](HangarBay)
* [Hull Integrity](HullIntegrity)
* [Normal Space Drive](NormalSpaceDrive)
* [Point Defense System](PointDefenseSystem)
* [Screen Generator](ScreenGenerator)

Military Systems
----------------

* [Main Battery](MainBattery)
* [Fighter Group](FighterGroup)
* [Missile System](MissileCraft)
* [Needle System](NeedleSystem)
* [Submunitions](Submunitions)
* [Torpedo System](TorpedoSystem)

Advanced Systems
----------------

* [Ablative Armor](AblativeArmor)
* [Advanced Hulls](AdvancedHulls)
* [Advanced Drive](AdvancedDrive)
* [Advanced FTL](AdvancedFtl)
* [Advanced Screen](AdvancedScreen)
* [Advanced Battery](AdvancedBattery)
* [Mega Battery](MegaBattery)
* [Railgun System](RailgunSystem)

Notes
-----

Systems are "fitted" to the hull.

This project uses a variation of the "merchant" ship design rules in _Full Thrust_, which standardizes some things across ship sizes like the cost of the [main drive](NormalSpaceDrive) and the number of hull rows. Unlike the merchant rules however, you are not limited to 10% of mass for ship systems; it is assumed actual merchant ships dedicate 40% of available mass to [cargo space](CargoSpace) and you are free to fit other systems if desired.
