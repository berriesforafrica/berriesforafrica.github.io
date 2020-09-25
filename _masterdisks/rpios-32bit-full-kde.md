---
title: "Masterdisk: RPI OS 32 Full KDE"
excerpt: "Creating an SSD with a 32-bit Raspberry Pi OS and a full suite of educative applications"
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
 

## Install the `kdeedu` applications suite 

Download and install the `kdeedu` package which is a bundle that contains all educative applications developed by the KDE Community. 

See [Installing Applications in RPI OS](/rpios/installing-apps/) for more information on how to install applications. 
{: .notice--warning}

All educative KDE Apps will now be downloaded and installed. This can take some time. 

Please note that this is a heavy download so make sure that you are connected to the Internet using a connection that can support large amounts of data.
{: .notice--warning}

After installation of the `kdeedu` meta package, the following additional apps will be available:

```
Education
└── Artikulate
└── Blinken
└── Cantor
└── KAlgebra
└── Kalzium
└── Kanagram
└── KBruch
└── KDE Marble
└── KGeography
└── KHangMan
└── Kig
└── Kiten
└── KLettres
└── KmPlot
└── KTouch
└── KTurtle
└── KWordQuiz
└── Minuet
└── Parley
└── Rocs
└── Step

Sound & Video
└── TiMidity++ MIDI sequencer

Games
└── Blinken
└── Kanagram
└── KHangMan

Preferences
└── TeXdoctk
```

After installation, the free disk space on a 120 GB SSD is as follows:

| Total | 110 GB |
| Used | 8.9 GB |
| Available | 95 GB |
| %Use | 9% |

## Install the `education-desktop-kde` applications suite 

Download and install the `education-desktop-kde` package which is a bundle that contains all educative applications developed by the KDE Community. 

See [Installing Applications in RPI OS](/rpios/installing-apps/) for more information on how to install applications. 
{: .notice--warning}

All educative KDE Apps will now be downloaded and installed. This can take some time. 

Please note that this is a heavy download so make sure that you are connected to the Internet using a connection that can support large amounts of data.
{: .notice--warning}

After installation of the `education-desktop-kde` meta package, the following additional apps will be available:

```
Education
└── AlgoBox
└── Avogadro
└── Chemtool
└── EasyChem Chemical Structures Editor
└── GChemPaint
└── GDIS Molecule Modeler
└── GeoGebra
└── Geoview
└── GNU Denemo
└── GNU Solfege
└── GPeriodic
└── GPredict
└── Grace
└── Graphmonkey
└── JFractionLab
└── Klavaro
└── KStars
└── OpenUniverse Space Simulator
└── Oregano
└── Piano Booster
└── Planets
└── PyMOL Molecular Graphics System
└── Stellarium
└── Viewmol
└── WordNet
└── XMabacus
└── xoscope

Office
└── Document Viewer
└── Gnumeric
└── KAddressBook
└── KOrganizer
└── Okular
└── Planner
└── VYM - View Your Mind

Internet
└── Firefox ESR
└── Gpredict
└── KDE Connect Indicator
└── Konqueror
└── Kopete
└── xoscope

Sound & Video
└── Audacious
└── Audacity
└── Dragon Player
└── Freebirth
└── GNU Denemo
└── GNU Solfege
└── GTick
└── Hydrogen
└── JuK
└── K3b
└── Lingpot
└── LMMS
└── MuseScore 2
└── NtEd
└── Pencil2D
└── Piano Booster
└── Qsynth
└── Rosegarden
└── terminatorX
└── tuxguitar
└── ZynAddSubFX - Alsa
└── ZynAddSubFX - Jack
└── ZynAddSubFX - OSS

Graphics
└── Dia
└── Document Viewer
└── GNU Image Manipulation Program
└── Gwenview
└── ImageMagick
└── Inkscape
└── LibreCAD
└── Okular
└── Pencil2D
└── PyMOL Molecular Graphics System
└── Scribus
└── XPaint

Games
└── Atomix
└── Cgoban
└── Einstein
└── gbrainy
└── GnuGo
└── Laby
└── Light Speed
└── LMemory
└── Ri-li
└── Tangrams
└── Xboard

System Tools
└── Discover
└── Dolphin
└── K3b
└── KDiskFree
└── Konsole
└── KSysGuard
└── KWalletManager
└── KwikDisk
└── MidnightCommander
└── UXTerm
└── XTerm

Accessories
└── Ark
└── Filelight
└── GoAdmin!
└── GoLearn!
└── GoNet!
└── GoOffice!
└── GoPlay!
└── GoSafe!
└── GoScience!
└── GoWeb!
└── Kate
└── KCalc
└── KCharSelect
└── KGpg
└── Klipper
└── KNotes
└── KTimer
└── KWrite
└── Midnight Commander Editor
└── Spectacle
└── Sweeper
└── TILP
└── XMabacus

Universal Access
└── KMag
└── KMouseTool
└── KMouth

Preferences
└── Apper
└── KDE Connect Settings
└── KDE System Settings
```

<div class='notice--info' markdown=1>
** Issue:** After installing these apps, the system requires a root password for any further installations. To set a `root` password, open a terminal and type the following command:
```
sudo passwd root
```
</div>


The free disk space on a 120 GB SSD is now as follows:

| Total | 110 GB |
| Used | 16 GB |
| Available | 89 GB |
| %Use | 15% |


## Add Additional Applications

Now add the following additional apps:

See [Installing Applications in RPI OS](/rpios/installing-apps/) for more information on how to install applications. 
{: .notice--warning}

```
kdenlive 
gcompris-qt 
kmymoney
skrooge
blender
digikam
kolourpaint
```

The free disk space on a 120 GB SSD is now as follows:

| Total | 110 GB |
| Used | 17 GB |
| Available | 88 GB |
| %Use | 16% |


## Final System Configs

Change the configuration of Chromium as follows:

<div class='notice--info' markdown=1>
Open Chromium

Go to `Settings` -> `Search Engine` 

Select `Google` 

Right of the address bar, click the` H264ify` icon and enable the option that avoids 60 fps videos (because the Pi has difficulties with that format)
</div> 
