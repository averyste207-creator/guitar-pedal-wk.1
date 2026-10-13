# Distortion Pedal

A DIY guitar distortion pedal project. This repository contains the circuit schematic and can be used to document the design, build process, testing, and future revisions.

## Circuit Schematic

![Distortion pedal circuit schematic](images/distortion-pedal-schematic.png)

## Overview

The schematic shows an analog distortion circuit built around an **LM741 operational amplifier**, with diode-clipping stages and adjustable controls.

- **Input:** Guitar signal input
- **Amplifier:** LM741 op-amp stage
- **Clipping:** Diodes provide signal clipping for distortion
- **Controls:** Potentiometers for adjusting the circuit response
- **Power:** 9 V supply is shown in the schematic
- **Output:** Distorted signal output

> This description is based on the current schematic. Confirm component values, pin connections, and power requirements before building the circuit.

## Components

The schematic includes the following parts (check the drawing and your chosen component footprints before ordering):

- LM741 operational amplifier
- 1N34A and 1N4148 diodes
- Resistors and capacitors as labeled in the schematic
- Potentiometers RV1 and RV2
- Input and output jacks
- 9 V power connection
- Breadboard or suitable PCB, hookup wire, and enclosure hardware

## Build Notes

1. Verify the schematic and component values.
2. Assemble the circuit on a breadboard before making a permanent PCB.
3. Check the power and ground connections before applying power.
4. Test with a low-volume amplifier setting first, then adjust the controls.
5. Record any changes to component values or wiring in this README.

## Project Status

**Status:** Schematic / prototype stage.

Build instructions, audio samples, enclosure details, and PCB files can be added as the project develops.

## Safety and Disclaimer

This is a low-voltage electronics project, but incorrect wiring can damage components or connected equipment. Double-check the power polarity and op-amp pinout before powering the circuit.

## License

No license has been specified yet. Add a `LICENSE` file if you want to define how others may use, modify, and distribute this project.
