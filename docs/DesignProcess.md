Design Process
--------------

Ship design in these rules is based on a [generic MASS unit](SizeWeightAndMass).

To start designing a ship, pick a [hull size](SizeWeightAndMass) between 2 and 100. This determines the ship's overall mass and space available for fitting systems. The table below is a rough guide to the general size of certain ships. For example, lets design a ["survey cruiser"](CuriousClassSurveyCruiser) of mass 48.

| Ship Type | Hull Size
| --------- | ---------
| Courier   | 2-20
| Cruiser   | 20-50
| Freighter | 40-60
| Tanker    | 60-100

The ship's [hull integrity](HullIntegrity) is the number of hull boxes or "hit points" it has. An average ship has 25% of its mass in hull integrity, while a military ship gets 50%. Our survey cruiser has 12 hull boxes.

Most ships will need a [normal space drive](NormalSpaceDrive) and a [faster-than-light](FasterThanLightDrive) drive system. You are required to have at least one [fire control system](FireControlSystem), which is part of the ship's on-board computer and sensor systems. Our survey cruiser has a main drive rated Thrust-4, a faster-than-light drive, and one fire control system.

All of the ship systems so far, as well as the structure of the ship, fuel tanks, crew accommodations, etc. take up 50% of the mass available, leaving the other 50% for you to fit additional systems as desired. The survey cruiser has 24 mass available, and as a research ship let's reserve 15 of that for [science facilities](CargoSpace#science). The remaining 9 mass is enough room to mount a superior sensor platform (mass 2), a [defensive screen](ScreenGenerator) generator (mass 3), two [point defense](PointDefenseSystem) systems (mass 2), and two Class-1 [batteries](MainBattery) (mass 2).

[Civilian systems](CivilianSystems) are generally available to fit to non-military ship hulls, while [military systems](MilitarySystems) are usually reserved for powerful war industries.

Notes
-----

Systems are "fitted" to the hull.

These documents standardize on a variation of the "merchant" ship design rules from _Full Thrust_.

- A hull strength of anywhere between 25% or 50% of hull mass can be bought for 2 points per mass, which in addition to the cost of 1 point per mass for the hull itself works out to exactly the same cost as Merchant vs. Military ships in the original rules.
- A normal space drive costs 1 point per mass of the ship &times; the desired thrust rating. This means military ships "escort" and "cruiser" size don't get cheaper thrust factors for now.
- All ships can fit 50% of overall mass in ship systems. Up to 40% of overall mass can be devoted to [cargo space](CargoSpace) or [hangar bays](HangarBay), but fitting more of those systems limits the amount of hull strength a ship can have.
- Tugs purchase oversize FTL systems that work a lot like cargo space. They are indicated by up to four boxes with the [FTL drive](FasterThanLightDrive) symbol and a number indicating that space's towing capacity. FTL towing capacity costs 2 points per mass of towing power, to a maximum of the ship's own mass, and should be split evenly between the four boxes.

*[FTL]: Faster Than Light


which standardizes some things across ship sizes like the cost of the [main drive](NormalSpaceDrive) and the number of hull rows. Unlike the merchant rules however, you are not limited to 10% of mass for ship systems; it is assumed actual merchant ships dedicate 40% of available mass to [cargo space](CargoSpace) and you are free to fit other systems if desired.
