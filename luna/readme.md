# Luna
Luna is a 108 key (104 US ANSI + 4 extra keys) keyboard with basic features. This does not have RGB lights, no speakers, no OLED screens... It's a keyboard that works.

This design is based on GH80-3003/GH80-3000. which is a universal board supporting both ISO and ANSI layout.

## Board info
- MCU: ATMEGA32U4
- Firmware: QMK (configured for Luna)
- Manual soldering needed: 3 LEDs and a USB B port

## Version info

v1.0 - Initial commit
v1.1 - Rerouted tracks
v1.2 - Rerouted tracks
v1.3 - Added graphics
v1.4 - Rerouted tracks
v1.5 - Fixed incorrect routing of USB line, removed redundant switches
v1.6 - Removed redundant components
v1.7 - Changed footprint to include AU/MU dual footprint (Note: This WILL result in DRC errors)
v1.8 - Moved RESET switch to the back
v1.9 - Changed names for the keys
v2.0 - Fixed track routing near mounting holes, replaced mounting holes with proper M3 mounting holes
