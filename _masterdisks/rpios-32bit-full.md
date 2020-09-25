---
title: "Masterdisk: RPI OS 32 Full"
excerpt: "Creating an SSD with a 32-bit Raspberry Pi OS"
toc: true
---

## Install Raspberry Pi OS Full (32-bit) on an SSD

Follow the procedure in [Raspbery Pi OS Full (32-bit) Installation](/rpios/installing-rpi-os-32-full/) to install the Raspberry Pi Operating System on an SSD.

Version `2020-08-20` of this OS comes with the following apps pre-installed:

```
Programming
└── BlueJ Java IDE
└── Geany
└── Greenfoot Java IDE
└── Mathematica
└── mu
└── Node-RED
└── Scratch
└── Scratch 2
└── Scratch 3
└── Sense HAT Emulator
└── Sonic Pi
└── Thonny Python IDE
└── Wolfram

Education
└── SmartSim

Office
└── LibreOffice Base
└── LibreOffice Calc
└── LibreOffice Draw
└── LibreOffice Impress
└── LibreOffice Math
└── LibreOffice Writer

Internet
└── Chromium Web Browser
└── Claws Mail
└── VNC Viewer

Sound & Video
└── VLC Media Player

Graphics
└── Image Viewer

Games
└── Boing
└── Bunner
└── Cavern
└── Minecraft Pi
└── Myriapod
└── Python Games
└── Soccer

Accessories
└── Archiver
└── Calculator
└── File Manager
└── PDF Viewer
└── Raspberry Pi Diagnostics
└── SD Card Copier
└── Task Manager
└── Terminal
└── Text Editor

Help
└── Bookshelf
└── Debian Reference
└── Get Started
└── Help
└── Projects

Preferences
└── Add / Remove Software
└── Appearance Settings
└── Keyboard and Mouse
└── Main Menu Editor
└── Raspberry Pi Configuration
└── Recommended Software
└── Screen Configuration
└── TeXdoctk
``` 

After installation of version `2020-08-20`, the free disk space on a 120 GB SSD is as follows:

| Total | 110 GB |
| Used | 7.6 GB |
| Available | 98 GB |
| %Use | 8% |

<div class='notice--info' markdown=1>
**Note:** You can at any time check the available dik space by opening a terminal and typing the following command:
```
$ df -h
```
</div>

## Final System Configs

Change the configuration of Chromium as follows:

<div class='notice--info' markdown=1>
Open Chromium

Go to `Settings` -> `Search Engine` 

Select `Google` 

Right of the address bar, click the` H264ify` icon and enable the option that avoids 60 fps videos (because the Pi has difficulties with that format)
</div> 

