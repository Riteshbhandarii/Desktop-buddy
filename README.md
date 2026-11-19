# Desktop Buddy

Desktop Buddy is an early-stage idea for a small, lively desktop robot built
from scratch. This repository is currently a hardware and software planning
space; the robot is not yet operational and will remain under development
until the target hardware and a working architecture are established.

## Current status

- Initial concept and repository setup
- No working hardware or software implementation yet
- Hardware selection and first bench tests are pending

## Target platform

The initial platform is intended to use a Raspberry Pi Zero 2 W (or a
compatible single-board computer). Final choices for motors, sensors,
actuators, power delivery, and the control software will be tested as the
hardware becomes available.

## Planned architecture

The project will be divided into independent responsibilities:

- **Hardware:** chassis, power distribution, motor drivers, servos, sensors,
  and Raspberry Pi mounting
- **Device interface:** safe, low-level control of motors and connected
  peripherals
- **Behavior:** desktop interactions and state-based movement
- **Application:** configuration, diagnostics, and a future user interface

This separation will allow hardware experiments to proceed without making
the whole system dependent on a single implementation.

## Development plan

1. Validate the Raspberry Pi and basic power supply.
2. Add and test a minimal motor or servo control prototype.
3. Introduce simple sensor input and safe shutdown behavior.
4. Build a basic behavior loop around the validated hardware.
