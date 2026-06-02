# Optical Flicker Generator

Firmware project for an Ethernet-connected optical flicker generator with:

- Web control page (`/`)
- Web configuration page (`/config`)
- HTTP JSON API
- ASCII shell over Serial and optional Telnet

## Documentation

- User manual: `firmware/USER_MANUAL.md`
- Interface/protocol reference: `firmware/PROTOCOL.md`

## Getting Started

1. Flash the firmware to the device.
2. Connect power and Ethernet.
3. Open the control page in a browser using:
   - `http://flicker-<suffix>.local/`, or
   - the IP shown on the device display.

## Repository Layout

- `firmware/` - PlatformIO firmware source and documentation
