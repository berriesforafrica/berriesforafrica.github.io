---
title: "Manjaro KDE - Apps"
excerpt: "Creating an SSD with Manjaro KDE and all KDE Applications"
toc: true
---

## Install the Manajaro KDE Operating System on an SSD

Follow the procedure in [Manjaro KDE Installation](/manjaro-kde/02-installing-manjaro-kde/) to install the Manajaro KDE Operating System on an SSD.

This default installation comes with the following apps pre-installed:

```
Development
└── Qt Assistant
└── Qt Designer
└── Qt Linguist
└── Qt QDbusViewer
└── UserFeedback Console

Education
└── Mathematics
    └── LibreOffice Math
└── Science
    └── LibreOffice Math

Graphics
└── Gwenview
└── LibreOffice Draw
└── Okular

Internet
└── Avahi SSH Server Browser
└── Avahi VNC Server Browser
└── Firefox

Multimedia
└── mpv Media Player
└── Qt V4L2 test utility
└── Qt V4L2 video capture utility
└── SMPlayer

Office
└── LibreOffice Base
└── LibreOffice Calc
└── LibreOffice Draw
└── LibreOffice Impress
└── LibreOffice Math
└── LibreOffice
└── LibreOffice Write
└── Okular

Settings
└── Add/Remove Software
└── Manjaro Settiings Manager
└── Software Update
└── System Settings

System
└── Add/Remove Software
└── Avahi Zeroconf Browser
└── Dolphin
└── Hardware Locality Istopo
└── Info Center
└── Konsole
└── KSysGuard
└── Software Update

Utilities
└── Ark
└── Emoji Selector
└── Kate
└── Spectacle

Lost & Found
└── mntray

Power / Session
└── Lock
└── Log Out
└── Switch User
└── Restart
└── Shutdown
``` 

As a reference, version 20.08 of the Manjaro KDE Operating System occupies about 10.1 GB of disk space. On a 120 GB SSD disk, this occupies about 9% of the available space (109.8 GB) and leaves 99.7 GB of disk space free.

## Install the full KDE applications suite 

Download and install the `kde-applications-meta` package which is a bundle that contains all applications developed by the KDE Community. 

See [Installing Applications in Manjaro KDE](/manjaro-kde/03-installing-apps/) for more information on how to install applications. 
{: .notice--warning}

When asked to choose a provider for `cron`, select `cronie`.
{: .notice--warning}

All KDE Apps will now be downloaded and installed. This can take some time. 

Please note that this is a heavy download of about 750 MB so make sure that you are connected to the Internet using a connection that can support such an amount of data.
{: .notice--warning}

After installation of the kde-applications-meta package, the following additional apps will be available:

```
Development
└── Translation
    └── Lokalize
└── Web Development
    └── KImageMapEditor
└── Akonadi Console
└── Cervisia
└── KAppTemplate
└── KCachegrind
└── KDevelop
└── KDevelop (Pick Session)
└── Kirigami Gallery
└── Kompare
└── KUIViewer
└── Umbrello

Education
└── Languages
    ├── Artikulate
    ├── Kanagram
    ├── KHangMan
    ├── Kiten
    ├── KLettres
    ├── KWordQuiz
    └── Parley
└── Mathematics
    ├── Cantor
    ├── KAlgebra
    ├── KAlgebra Mobile
    ├── KBruch
    ├── Kig
    ├── KmPlot
    └── Rocs
└── Miscellaneous
    ├── Blinken
    ├── KGeography
    ├── KTouch
    ├── KTurtle
    ├── Minuet
    └── Step
└── Science
    ├── Cantor
    ├── KAlgebra
    ├── KAlgebra Mobile
    ├── Kalzium
    ├── KDE Marble
    └── Rocs

Games
└── Arcade
    ├── Bomber
    ├── Granatier
    ├── Kapman
    ├── KBlocks
    ├── KBounce
    ├── KBreakOut
    ├── KGoldrunner
    ├── Kolf
    ├── Kollision
    ├── KSnakeDuel
    └── KSpaceDuel
└── Board Games
    ├── Bovo
    ├── Kajongg
    ├── KBlackBox
    ├── KFourInLine
    ├── Kigo
    ├── Kiriki
    ├── KMahjongg
    ├── Knights
    ├── KReversi
    ├── KSquares
    └── Shisen-Sho
└── Card Games
    ├── KPatience
    └── LSkat
└── Games for Kids
    ├── Blinken
    ├── Kanagram
    ├── KHangman
    └── Potato Guy
└── Logic Games
    ├── KDiamond
    ├── KSudoku
    ├── Kubrick
    ├── Palapeli
    └── picmi
└── Tactics & Strategy
    ├── KAtomic
    ├── Killbots
    ├── KJumpingCube
    ├── Klickety
    ├── KMines
    ├── KNetWalk
    ├── Kolor Lines
    ├── Konquest
    ├── KsirK Skin Editor
    ├── KsirK
    ├── Naval Battle
    └── SameGame

Graphics
├── KolourPaint
└── More Applications
    ├── KColorChooser
    └── KRuler

Internet
├── Akregator
└── Contact Print Theme Editor
└── Contact Theme Editor
└── IM Contacts
└── KDE Connect
└── KDE Connect SMS
└── KDE IM Log Viewer
└── KGet
└── KMail Header Theme Editor
└── KMail
└── Konqueror
└── Kopete
└── KRDC
└── Krfb
└── KTnef
└── Open on connected device via KDE Connect
└── PIM Data Exporter
└── Sieve Editor

Multimedia
├── Dragon Player
└── Elisa
└── JuK
└── K3b
└── Kamoso
└── Kdenlive
└── KMix
└── Kwave Sound Editor
└── VLC media player

Office
├── Contact Print Theme Editor
└── Contact Theme Editor
└── KAddressBook
└── KMail Header Theme Editor
└── KMail
└── Kontact
└── KOrganizer
└── KTnef
└── Lokalize
└── Sieve Editor

System
├── KDiskFree
└── KSystemLog
└── KWalletManager
└── KwikDisk
└── Yakuake	

Utilities
├── Filelight
└── KAlarm
└── KBackup
└── KCalc
└── KCharSelect
└── KFind
└── KFloppy
└── KGpg
└── Kleopatra
└── KMag
└── KMail Import Wizard
└── KMouseTool
└── KMouth
└── KNotes
└── KTeaTime
└── KTimer
└── KTnef
└── KWrite
└── Sweeper
```

As a reference, version 20.08 of the kde-applications-meta package, occupies about 3.5 GB of disk space. 

On a 120 GB SSD disk, about 12% of the available space (109.7 GB) is now occupied and about 96.2 GB of the total disk space is free.

## Add Additional Applications

Now add the following additional apps:

See [Installing Applications in Manjaro KDE](/manjaro-kde/03-installing-apps/) for more information on how to install applications. 
{: .notice--warning}

```
Chromium Web Browser
KDE Partition Manager
exfat-utils
GNU Image Manipulation Program (GIMP)
Blender
Shotwell
Inkscape
digiKam
Scratch
LibreCAD
Scribus
GCompris
Krita
KMyMoney
```

As a reference, installing these apps in version 20.08 of Manjaro occupies about 2.9 GB of disk space. 

On a 120 GB SSD disk, about 15% of the available space (109.7 GB) is now occupied and about 93.3 GB of the total disk space is free.


## Final System Configs

## Firefox

<div class='notice--info' markdown=1>
Right-click on the Firefox icon in the bottom Task Manager

Unpin from Task Manager

Right-click on the Firefox icon in the Favourites section of the Application Launcher

Remove from Favourites
</div>


## Chromium

<div class='notice--info' markdown=1>
Drag the Chromium icon in the Application Launcher into the Task Manager

Right-click the the Chromium icon in the Application Launcher

Add to Favourites

Chromium Settings -> Make Default Web Browser
</div>

## Automatic Login

<div class='notice--info' markdown=1>

`Application Launcher` -> `Applications` -> `Settings` -> `System Settings`

Select `Personalization`

Select `Account Details`

Select user `pi`

Enable `Log in automatically`

Provide the `pi` password
</div>