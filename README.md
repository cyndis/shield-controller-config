Shield Controller Config
========================

This repo contains some files to make the NVIDIA Shield Controller work on Linux/SDL2.

- 99-shield-controller.rules: Udev rules to make the controller be classified as a joystick.
  Since it has a touchpad it is by default classified only as a mouse.
- gamecontrollerdb.txt: SDL2 game controller configuration to make the controller available through
  the game controller API.
