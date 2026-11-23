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

## Schematic V3 — Protection Circuit Development and Design Review

Version 3 builds on the previous schematic by further developing the battery-protection and motor-current monitoring systems.

**Key updates:**
- Expanded the LM393 comparator circuitry for battery undervoltage detection.
- Added a MOSFET-based battery cutoff stage.
- Developed motor overcurrent detection using the existing LM358 current-sensing circuit.
- Added an overcurrent alert signal to the Arduino Nano.
- Updated provisional resistor values and voltage thresholds.
- Selected a proposed 6S2P configuration using standard 1.5V alkaline AA batteries.

**Current Status: Design Review**

The schematic has reached a preliminary design-review stage. Battery protection, fuse and component ratings, power distribution, and shutdown behavior still require verification.

The next phase will involve incorporating team-lead feedback, finalizing the electrical design, and preparing for physical assembly and testing.

[View Schematic V3](Motorsports_Onboarding_Schematic3.pdf)

## Building Progress Log

**November 21, 2026 — 555 Timer LED Blinking Circuit**

Objective: Build and test an LED blinking circuit using a 555 timer IC.

Successfully demonstrated an LED blinking using a 555 timer configured in astable mode. In this configuration, the timer continuously switches its output between HIGH and LOW, allowing the LED to blink automatically without requiring an Arduino or programmed instructions.

The blinking frequency is controlled by the resistors and capacitor connected to the timer. As the capacitor charges and discharges, the 555 timer switches its output, turning the LED on and off.
