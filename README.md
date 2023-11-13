# Flambehub

![Flambehub_0 2_1](https://github.com/Ccecil/Flambehub/assets/1588588/a6e053fa-dfbe-4287-8464-eb01103bf52a)

Flambehub is an attempt at a hardware failsafe board for 3d printers (and other devices) and is intended to function standalone as a "dumb" device with no MCU.  All triggers are set by hardware failsafes which are optional.  
Should help prevent issues due to failed control (stuck FET) or in case of MCU watchdog failure.
Allows attachment of human safety devices such as smoke/flame alarms, E stop buttons, light curtains...etc.

-8 hardware failsafe trigger inputs
-1 MCU enable/disable input for being driven by the "Halt" signal from the device under control
-Up to 30a @28V DC
-Inline fuse
-Buffered and debounced input controls prevent unintentional triggers.
-Onboard 5v regulator option via Recom regulator

This device connects in the main DC power line between the PSU and the control board.
