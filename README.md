# VH-OSC v1.0 Reference Guide
This an official reference for [Virtual Handheld](https://vhvr.carrd.co/)'s [OSC](https://opensoundcontrol.stanford.edu/) functionality, made for VR avatar creators and asset developers.

# Avatar Parameter List
| Display Name        | Parameter Name      | Type | Range        | Description                                                              |
|---------------------|---------------------|------|--------------|--------------------------------------------------------------------------|
| Handheld On         | VH/Handheld_On      | Bool | True / False | Is the virtual handheld toggled on?                                      |
| Bindings Profile    | VH/Bindings_Profile | Int  | 0 - 255      | The currently selected bindings profile in the Bindings menu             |
| Gamepad Type        | VH/Gamepad_Type     | Int  | 0 - 2        | The currently connected gamepad type; None = 0, Xbox = 1, DualShock = 2  |
| Main Screen Enabled | VH/Screens_Main     | Bool | True / False | Is the main screen of the handheld enabled?                              |
| Top Screen Enabled  | VH/Screens_Top      | Bool | True / False | Is the top screen of the handheld enabled?                               |
| Color Profile       | VH/Color_Profile    | Int  | 0 - 255      | The currently selected color profile in the Colors menu                  |
| Track Handheld To   | VH/Tracker_Mode     | Int  | 1 - 5        | Left Hand = 1, Right Hand = 2, Head Look = 3, Custom = 4, Both Hands = 5 |
