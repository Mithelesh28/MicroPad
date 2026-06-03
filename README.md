# Micropad

A custom 6-key macropad built around the Seeed Studio XIAO RP2040, featuring two rotary encoders, RGB lighting, and Cherry MX mechanical switches.

## Features

* 6 programmable mechanical keys
* 2 rotary encoders with push-switch support
* 2 SK6812 MINI-E RGB LEDs
* USB-C connectivity via Seeed Studio XIAO RP2040
* Custom PCB designed in KiCad 9
* Custom enclosure designed in Fusion 360
* KMK firmware support

## Hardware

### Microcontroller

* Seeed Studio XIAO RP2040

### Switches

* 6 × Cherry MX compatible switches

### Rotary Encoders

* 2 × EC11 rotary encoders

### RGB Lighting

* 2 × SK6812 MINI-E addressable RGB LEDs

## Key Layout

| Key | Function         |
| --- | ---------------- |
| SW3 | D                |
| SW4 | Copy (Ctrl + C)  |
| SW5 | S                |
| SW6 | W                |
| SW7 | A                |
| SW8 | Paste (Ctrl + V) |

## Encoder Functions

### Encoder 1

* Clockwise → Volume Up
* Counter-clockwise → Volume Down

### Encoder 2

* Clockwise → Brightness Up
* Counter-clockwise → Brightness Down

## PCB Design

Designed using KiCad 9.

### Main Components

* Seeed Studio XIAO RP2040
* Cherry MX footprints
* EC11 rotary encoders
* SK6812 MINI-E RGB LEDs

## Firmware

Planned firmware stack:

* CircuitPython
* KMK Firmware

The firmware will support:

* Custom key mappings
* Rotary encoder controls
* RGB effects
* Media controls

## CAD

The enclosure and assembly are designed in Fusion 360.

## Manufacturing Files

This repository contains:

* KiCad project files
* PCB manufacturing files (Gerbers)
* STEP assembly model
* Fusion 360 enclosure files
* Firmware source code

## Future Improvements

* Additional RGB effects
* Multiple layers and macros
* OLED display support
* Custom encoder functions
* VIA/Vial compatibility

## License

MIT License

