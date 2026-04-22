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

# VH Set Up
To use Virtual Handheld's OSC functionality, you must first enable it on the OSC in the Virtual Handheld Settings. (VH Settings can be found in your SteamVR dashboard or on your desktop by double clicking the [VH] system tray icon.)

![OSC Master Toggle](VH-OSC-Master-Toggle.png)

## Enable OSC Chatbox
If you want a "Playing on Virutal Handheld" chatbox to appear over your avatar in VRChat when you are using the handheld, you must enable it on the Chatbox tab in the VH Settings.

**Other users can see this chatbox. Please be mindful of others when using this feature.**

![OSC Chatbox Toggle](VH-OSC-Chatbox-Toggle.png)

## Enable OSC Avatar Parameters
If you want VH to send parameters for controlling things such as avatar animations, prop toggles, etc., you must enable them in Avatar tab in the VH Settings.

Note that you must be in an avatar that supports the supplied parameters in order to make use of this feature.
![OSC Avatar Parameters Toggle](VH-OSC-Avatar-Params-Toggle.png)
