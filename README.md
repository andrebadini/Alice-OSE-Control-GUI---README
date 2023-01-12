# Alice OSE Control (GUI)

Unofficial multi-platform app to control Alice Open Source Exoskeleton, written in Dart/Flutter.

Check out the **Alice OSE (Open Source) Exoskeleton** page at [Indi Global Page](http://www.indi.global/aliceose).

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/aliceLight.png?raw=true" width="160%"/>

## Features
- Multi-Platform:
- USB-serial connection to the PID control (Arduino) of the exoskeleton (with C library under the hood);
- Multi language support;
- Console with desktop multi window, for debugging purpose;
- Profile page to manage users profile and sessions data (steps taken; date/time; elapsed time; distance walked).
- Super fast NoSQL ACID database;
- Setting menu for system customization:
  - Dark/light mode;
  - Window transparency;
  - Navigation pane display mode;
  - Accent color;
  - Text direction;
  - Locale (language/internationalization).

## Platforms

| Platform | Status | Minimum Version |
|----------|--------|-----------------|
| Windows  | ✅      | 10 or later     |
| macOS    | ✅      | BigSur or later |
| Android  | ⛔     | -               |


---
# Screenshots

## ManageConnection

`Connection` is the initial menu for manage connections to the serial port of the Exoskeleton.

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/darkMode.png?raw=true"/>

It has a stream to listen serial port event (device attachment). 

Supports a `usb-serial` and `bluetooth`connection (bluetooth is not ready at Arduino side).

## StandingMenu

Provides controls of the Exoskeleton, such as stepping, walking routine, sitting, and others controls.

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/standing.png?raw=true" width="75%"/>

Besides, provides automatic counting and control of session time and steps.

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/stepsControl.png?raw=true" width="75%"/>

## GeneralMenu

Provides controlled exoskeleton movements.

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/generalMenu.png?raw=true" width="75%"/>

## ProfilePage
On the profile page it is possible to add, change or delete users.

User session logs are saved locally (NoSQL) and shown in this menu, where the user can manage it.

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/profile.png?raw=true" width="75%"/>

## Console

Option for any need for debugging, it opens in a second window and provides information about sending and receiving commands to the serial port.

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/console.png?raw=true" width="45%"/>


## Settings

### Theme Mode

| Dark Theme                                                                                                                         | Light Theme                                                                                                                                    |
|------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/darkMode.png?raw=true"/> | <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/standingLightWindows.png?raw=true" width="75%"/> |

### Navigation Pane Display Mode


| Top                                                                                                                    | Open                                                                                                                  |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/top.png?raw=true"/>      | <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/open.png?raw=true"/>    |
| Compact                                                                                                                | Minimal                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------    | --------------------------------------------------------------------------------------------------------------------  |
| <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/compact.png?raw=true"/> |   <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/minimal.png?raw=true"/>                                                                                                                    |                                                                                                                    |


### Window Transparency

There are 14 types of window transparency available for **macOS** and 6 for **Windows**.


| macOS window effect                        | Windows window effect                      |
|--------------------------------------------|--------------------------------------------|
| <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/transparencyMacOS.png?raw=true"/> | <img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/standingDarkWindows.png?raw=true"/> | 


### Accent Color
<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/accentColor.png?raw=true"/>


### Locale

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/locale.png?raw=true"/>



# TODO

| TODO                | Status       | Comment                                                                                                        |
|---------------------|--------------|----------------------------------------------------------------------------------------------------------------|
| History charts      | 🗹 not started | Build beautiful and interactive charts to show user history data of the sessions.                              |
| Voice Control       | 🗹 not started | Control exoskeleton with voice commands.                                                                       |
| App optimization    | 🗹 not started | Review and refactor code to increase app performance (less usage of hardware resources).                       |
| Android release     | 🗹 not started | Android version was not released yet because of an issue with usb permission on some versions of the platform. |
| Add macOS design    | 🗹 not started | Implement macOS design for macOS (the current app's design follows the Fluent UI for Windows only).            |
| Add material design | 🗹 not started | Implement material design for Android (the current app's design follows the Fluent UI for Windows only)..                                                                        | Add wireless connection | 🗹 not started | Add wireless connection to the exoskeleton.                                                                        |
|

