## Integreverse Space Engineers

This Space Engineers server and mod pack aims at prolonging the Space Engineers experience by introducing a tiered progression system for ores, functional blocks, weapons, and NPCs.
It adds new mechanics in the form of water (buoyancy) and atmosphereic friction (planes/wings/glide, reentry heat).

## Progression
-----------

Progression is implemented roughly as 1 tier per planet. I.e.: on the tier 3 Planet the NPCs have tier 3 equipment, you find tier 3 ore and can use it to craft tier 3 blocks.
The intenden Progression path is as follows.:
- Earth: start here. Build hydro thrusters to reach earths moon.
- Moon: youll find ore required for jumpdrives as well as gold and silver.
- with the jumpdrive you can reach 4 planets of comparable tier (in any order you choose). After all 4 planets every block type is available. Further planets (T3 to T5 just improove performance of those blocks).
-- Mars: Platinum and a new ore required for ion thrusters
-- Alien: Uranium -> reactors
-- Europa (Mars Moon): New ore required exclusively for energy shields
-- Archipelagos (water plnaet): T2 Ore - the first tiered ore that allows to build more efficient versions of all blocks.
- Triton: T3 Ore
- Petram: T4 Ore
- Titan: T5 Ore
Compared to vanilla there is no silver/gold/uranium in asteroids.

## Water
-----

The planet Archipelagos was added to the solar system. Its surface is mainly covered in Water. The T2 Ore located there needs to be mined under water.
Thrusters were modified such that Atmosphereic-, Ion- and Hydrogenthrusters will turn off once submerged.
There is a new type of thrusters called "Waterthrusters" which - for the lack of a 3D model - look like Atmospheric thrusters.
The Waterthrusters are switched off by the game if NOT submerged in water.
The water mod "calculates buoyancy based on gas tanks below the water ... It behaves like you would expect a gas tank in water would and allows for submarines.
You can make a submarine by using collectors as ballasts, they collect ice. Hydrogen gas is more buoyant the oxygen gas."
Pirates - "Violets are blue, roses are red. We're coming aboard. Prepare to eat lead."

## Atmospheric physics

-------------------
Implemented by this mod.: https://steamcommunity.com/sharedfiles/filedetails/?id=571920453
"Adds drag to all ships in atmosphere. Adds deadly reentry to the game. Adds wind to the game."
You can configure Aerodynamic Control Surfaces (wings/flaps and such) via the custom datafield of blocks. see https://steamcommunity.com/sharedfiles/filedetails/?id=800500312
There is multiple other mods adding plane parts like wings wheels and so on implemented as well.

## DAKKA
-----

All weapons are based on the WeaponCore mod which adds physics like ballisic curves, damage decrease over range, AoE for HE ammo, damage on impact, penetration before explosion, multiple ammo types for the same weapon (HE, AP, ...), guided missiles, energy weapons with increased damage vs shields but reduced damage vs matter (vice versa for kinetic weapons).
There are about 30 new weapons which unlock over the various tiers.

## H2 rebalance
------------

We made Hydrogen thrusters stronger and tanks last longer and placed ionthrusters a little bit further back in the techtree compared to vanilla for a prolonged H2 vessel phase.
The water on Archipelagos as the "collector" block allow for an unlimited source of ice and thus fuel. We added smaller small grid tanks. All tank volumes are based on actual block volumes - double the block size double the volume you can fill in.
To balance this improovement a bit we made H2 Tanks explode when damaged (based on fill level). Reactors also explode when damaged.

## Jetpack nerfed
--------------

to incentivise use of vehicles, welding/grindingships, cranes and similar machines. We felt that building machines is what the game is about and the player should not be more efficient in these things compared to contraptions.
