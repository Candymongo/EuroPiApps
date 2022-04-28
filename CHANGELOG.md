# Change Log

### 2022-04-04

- release version 0.3.0
- add save/load script state behavior via EuroPiScript
- add Strange Attractor chaotic modulation script
- add Noddy Holder sample/track and hold script

### 2022-03-16

- release version 0.2.0

### 2022-03-16

- add bootloader menu allowing the user to choose a script to run
- update all existing scripts to work with the menu
- add new firmware module 'europi_script' containing a base class to support menu inclusion
- add new firmware module 'ui' as a place to hold reusable UI components

### 2022-03-10

- release version 0.1.0

### 2022-02-18

- update diagnostic script to add temperature display and CV output rotation.

### 2022-02-15

- add Consequencer script

### 2022-02-04

- Add support for automated testing
- Add scope script

### 2022-02-01

- added {meth}`europi.DigitalReader.handler_falling()` To define a callback function to call when a falling edge is detected

### 2021-10-15 - 2022-02-02

- initial development of EuroPi library and documentation, including the following scripts:
  - calibrate
  - coin_toss
  - diagnostic
  - harmonic_lfos
  - polyrhythmic_sequencer
  - radio_scanner