# Saturn V for RSS/RO
A Saturn V craft file for Realism Overhaul/Real Solar System.

## Features
* Fully simulated Saturn V: S-IC, S-II, S-IVB, LM, CSM

### Engines
* S-IC (RP1/LOX): 5 x Rocketdyne F-1
* S-II (LH2/LOX): 5 x Rocketdyne J-2
* S-IVB (LH2/LOX): 1 x Rocketdyne J-2
* LM DPS (N2H4+UDMH/N2O4 [Helium Pressurized]): 1 x Lunar Module Descent Engine
* LM APS (N2H4+UDMH/N2O4 [Helium Pressurized]): 1 x Lunar Module Ascent Engine
* SPS (N2H4+UDMH/N2O4 [Helium Pressurized]): 1 x Aerojet-General AJ10-137

## How to Use
In order to use this craft file, simply install the dependencies (CKAN recommended) and load the craft file into your saves folder.

### Primer Vector Guidance (MechJeb 2)
In order to use this craft with PVG autopilot:
* Turn on RCS (The actual RCS thrusters are activated in later stages, so it is perfectly realistic here)
* Select a target orbit of 185 x 185 kilometers
* Set the last stage and early shutoff stage to 3
* Set the booster pitch rate to 0.2 degrees per second
* Set the last stage of autostage to stage 6 (**REMEMBER TO MANUALLY STAGE AFTER LIFTOFF**)

## Dependencies
* Realism Overhaul/Real Solar System/Realistic Progression 1 Express Install
* ASET (for working capsule IVA)
* Internal RCS

## Problems
* Since the RO suite doesn't come with an Auxiliary Propulsion System that was used on the real S-IVB, I used modular RCS instead, so it is not entirely realistic.

## Changelog
* 1.4 - Created this GitHub repository.
* 1.3 - Removed gimbal from the center J-2 engine of the S-II.
* 1.2 - Removed gimbal from the center F-1 engine of the S-IC.
* 1.1 - Added insulation to all Rocketdyne F-1 engines.
* 1.0 - Craft file created.
