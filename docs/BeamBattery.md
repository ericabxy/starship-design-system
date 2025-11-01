Beam Battery
------------

Particle accelerator offensive weapon system. Several individual particle beam projectors are mounted in a "battery" that can fire on a single target within range and firing arc. See [Range and Bearing](RangeAndBearing) for details on how to find direction and distance to targets.

To determine the effect of firing on a target, a number of dice are rolled depending on range. Class 3 batteries have a range of 36&Prime;. When firing at a range of 0-12&Prime;, three dice are rolled; at 12-24&prime;, two dice; and at 24-36&Prime;, one die. The following table shows the number of dice to roll indexed by battery class and range to target.

| Range      | Class 1 | Class 2 | Class 3 | Class 4
| ---------- | ------- | ------- | ------- | -------
| **0-12″**  | Roll 1D | Roll 2D | Roll 3D | Roll 4D
| **12-24″** | ---     | Roll 1D | Roll 2D | Roll 3D
| **24-36″** | ---     | ---     | Roll 1D | Roll 2D
| **36-48″** | ---     | ---     | ---     | Roll 1D

Damage is dealt according to the results of the dice. The target ship must cross off a number of <span class='hull-boxes'>j</span>hull boxes according to the total damage points generated as detailed in this table.

| Results                 | Damage
| ----------------------- | ------
| Every 1, 2, or 3 rolled | No effect
| Every 4 or 5 rolled     | One damage point
| Every 6 rolled          | Two damage points

Defensive [screens](ScreenGenerator) reduce the damage from beam batteries.

| Results                    | Screen Level 1    | Screen Level 2
| -------------------------- | ----------------- | --------------
| Every 1, 2, 3, or 4 rolled | No effect         | No effect
| Every 5 rolled             | One damage point  | One damage point
| Every 6 rolled             | Two damage points | One damage point

Symbols:

<div class='ship-diagram'>
    <div class='beam-battery beam-battery--3-arc -fs'>
      <div class='beam-battery__class'>3</div>
    </div>
    <div class='beam-battery beam-battery--1-arc'>
      <div class='beam-battery__class'>2</div>
    </div>
    <div class='beam-battery'>
      <div class='beam-battery__class'>1</div>
    </div>
</div>

<div class='ship-diagram'>
  <div>
    <div class='beam-battery beam-battery--1-arc'>
      <div class='beam-battery__class'>3</div>
    </div>
  </div>
  <div>
    <div class='beam-battery beam-battery--3-arc -fp'>
      <div class='beam-battery__class'>2</div>
    </div>
    <div class='beam-battery beam-battery--3-arc -fs'>
      <div class='beam-battery__class'>2</div>
    </div>
  </div>
</div>

Class-1 Point Defense Mode
--------------------------

Class 1 beam batteries can be fired in defense against approaching small craft and missiles. This requires the use of one [fire control](FireControlSystem) system, but this one can be shared among any number of Class 1 batteries being used in point defense mode.

1D6 is rolled as normal, but only one hit is scored on a roll of **5** or **6** (as if being affected by level-2 screens).

Class-2 Needle Mode (experimental)
----------------------------------

At a range of 9&Prime;, a Class-2 battery can target and knock out a ship's systems. This requires the dedicated use of a [FireCon](FireControlSystem), and to determine the effect roll *one D6*.

**Needle Mode Effects:**

| Roll results | Effect
| ------------ | ------
| 1-3          | No effect
| 4-5          | One damage point
| 6            | One damage point AND target system knocked-out

Design Costs
------------

| Type of System  | Mass | Cost
| --------------- | :--: | ----
| Class 1 Battery | 1    | 2 points + 1/arc
| Class 2 Battery | 2    | 3 points + 2/arc
| Class 3 Battery | 3    | 4 points + 3/arc
| Class 4 Battery | 5    | 5 points + 4/arc
| Class 5 Battery | 8    | 6 points + 5/arc

Penetrating Damage
------------------

Ships using the old design rules tend to have far fewer hull boxes, so standard batteries do not re-roll sixes to deal extra damage in this game.
