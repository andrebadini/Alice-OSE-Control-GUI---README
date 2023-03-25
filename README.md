# Alice OSE Control (GUI)

Unofficial multi-platform app to control Alice Open Source Exoskeleton, written in Dart/Flutter.

Check out the **Alice OSE (Open Source) Exoskeleton** page at [Indi Global Page](http://www.indi.global/aliceose).

Windows:

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/Captura%20de%20tela%202023-01-12%20215926.jpg?raw=true" width="160%"/>


macOS:

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

<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/darkTransparency.png?raw=true" width="160%"/>


<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/standingLightWindows.png?raw=true" width="160%"/>


<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/consoleMultiWindow.png?raw=true" width="160%"/>


<img src="https://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/generalMenu.png?raw=true" width="160%"/>


<img src="hhttps://github.com/andrebadini/Alice-OSE-Control-GUI---README/blob/main/Screenshots/profile.png?raw=true" width="160%"/>



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

