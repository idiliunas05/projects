# BU Motorsports — Motor Control Project

Documentation of my Arduino-based DC motor control project.

## Project Progress
- Initial circuit design
- KiCad schematic development
- Circuit testing and revisions

## Schematics
The following schematic versions document the development of the electrical system, from the initial motor-control design to expanded sensing and battery-protection circuitry.

## Schematic V1
Initial KiCad schematic for an Arduino-based
DC motor control system.

[View Schematic V1](Motorsports_Onboarding_Schematic1.pdf)

## Schematic V2 — Current Sensing and Battery Protection

Version 2 expands the initial motor-control schematic with additional monitoring and protection circuitry.

**11/14 Key updates:**
- Added shunt-based motor current sensing with an LM358 operational amplifier.
- Incorporated signal filtering for Arduino current measurements.
- Expanded the battery system into a series-parallel configuration.
- Added preliminary MOSFET-based power cutoff circuitry.
- Introduced LM393 comparator circuits for battery-voltage monitoring and protection.

The design is still in progress. Battery protection thresholds, component ratings, and final electrical validation have not yet been completed.

[View Schematic V2](Motorsports_Onboarding_Schematic2.pdf)
