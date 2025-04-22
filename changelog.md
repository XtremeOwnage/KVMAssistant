## Change History

### Version 2

1. Removed 4th KVM Input.
2. Removed Optocoupler array, Use 3 unused ports from ULN2003A instead.
3. Removed resistors on LED lines. LEDs are 3.3-5v tolerant. 
4. Removed resistors from optocoupler.
5. Added test pads. Added serial headers.
    - Kind of a PITA to troubleshoot when you cannot hook onto any of the SMT components.
6. Added front/rear ground planes.
7. Updated footprint to leverage COMMONLY available ESP32 Devkit footprints, and not the obscure 48pin one from version 1.
8. Added ability to globally enable/disable all LEDs via ESP.
    - Useful if you want to be able to turn all of the LEDs on or off.
9. Simplified everything.
10. Added mounting holes
11. Added labels everywhere.
    - Much easier to troubleshoot when everything is labeled.
12. Added a REALLY bad pun to the silkscreen.

#### Version 2.1

1. Removed copper fill behind ESP's antenna