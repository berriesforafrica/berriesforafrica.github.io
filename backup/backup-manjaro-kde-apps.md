---
title: "BACKUP - Manjaro KDE - Apps"
excerpt: "Creating an SSD with Manjaro KDE and all KDE Applications"
toc: true
---

## Install the Manajaro KDE Operating System on an SSD

Download the [latest version of Manjaro KDE for Raspberry Pi](https://manjaro.org/download/#raspberry-pi-4-kde-plasma) and install it on an SSD. 

To install an Operating System on an SSD, see [Installing Operating System images]({{ "" | relative_url }}../installing-operating-systems/).
{: .notice--warning}

## Initial Boot Setup

Connect the SSD to the Raspberry Pi using the SSD-to-USB adapter and start the Raspberry Pi.

**Note** The SSD adapter must always be connected to one of the blue USB ports! The blue USB ports are high speed USB 3.0 ports that provide the best performance. The black USB ports are low-speed USB 2.0 ports. If you connect your SSD disk to these low-speed ports, your Raspberry Pi will become very slow. 
{: .notice--warning}


**Note** You start the Raspberry Pi by connecting the power cable to it. But you can never stop the Raspberry Pi by unplugging the power. Doing so might damage the SSD and can make it unusable. Always stop the Raspberry Pi by using the appropriate menu entries for Shutting Down or Restarting the system.
{: .notice--danger}

A text-based setup wizard appears. Provide it the following info:

| Configuration | Value |
| --- | --- |
| Keyboard Layout | `us` | 
| Username |  `pi`
| Full name of `pi`| `pi`
| Password for `pi`| Since you are creating a master disk, supply the default agreed password
| Password for `root`| Since you are creating a master disk, supply the default agreed password
| Time Zone|  `Africa/Maputo` 
| Locale|  `en-ZW.UTF-8` 

Login into the system as user `pi` and provide the password for user `pi`.

Update the System:

`Application Launcher` -> `Applications` -> `System` -> `Software Update`<br>
Press `Apply`<br>
Provide root password<br>
Press `Apply`<br>
{: .notice--info}


**1.** `Application Launcher` -> `Applications` -> `System` -> `Software Update`<br>
**2.** Press `Apply`<br>
**3.** Provide root password<br>
**4.** Press `Apply`<br>
{: .notice--info}


<div class="notice--info" markdown="1">
**Step1:**  `Application Launcher` -> `Applications` -> `System` -> `Software Update`

**Step2:** Press `Apply`

**Step3:** Provide root password

**Step4:** Press `Apply`
</div>


<div class="notice--info" markdown="1">
**Step1:**  `Application Launcher` -> `Applications` -> `System` -> `Software Update`<br>
**Step2:** Press `Apply`<br>
**Step3:** Provide root password<br>
**Step4:** Press `Apply`<br>
</div>


Reboot (= restart) the system:

`Application Launcher` -> `Leave` -> `Restart`
{: .notice--info}

You SSD now contains a default installation of the Manjaro KDE Operating System.

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

To get the best experience, you can download the `kde-applications-meta` package which is a bundle that contains all applications developed by the KDE Community. 

Please note that this is a heavy download of about 750 MB so make sure that you are connected to the Internet using a connection that can support such an amount of data.
{: .notice--warning}

Using `<br>`

`Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`
Click on the search icon<br>
Type `kde-applications-meta`<br>
Click on the `Install` button at the right of `kde-applications-meta`<br>
Authorise the operation using the root password<br>
**NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>
Choose a provider for `cron`. Select `cronie`.<br>
Press `Apply`<br>
All KDE Apps will now be downloaded and installed. This can take some time. 
{: .notice--info}

or using paragraphs inside a div:

<div class="notice--info" markdown="1">
`Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`

Click on the search icon<br>

Type `kde-applications-meta`<br>

Click on the `Install` button at the right of `kde-applications-meta`<br>

Authorise the operation using the root password<br>

**NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>

Choose a provider for `cron`. Select `cronie`.<br>

Press `Apply`<br>

All KDE Apps will now be downloaded and installed. This can take some time. 
</div>

or using paragraphs inside a div with steps:

<div class="notice--info" markdown="1">
**Step1:** `Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`

**Step2:** Click on the search icon<br>

**Step3:** Type `kde-applications-meta`<br>

**Step4:** Click on the `Install` button at the right of `kde-applications-meta`<br>

**Step5:** Authorise the operation using the root password<br>

**NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>
{: .notice--warning}

**Step6:** Choose a provider for `cron`. Select `cronie`.<br>

**Step7:** Press `Apply`<br>

All KDE Apps will now be downloaded and installed. This can take some time. 
</div>

or using a bullet list :
- `Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`
- Click on the search icon<br>
- Type `kde-applications-meta`<br>
- Click on the `Install` button at the right of `kde-applications-meta`<br>
- Authorise the operation using the root password<br>
- **NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>
- Choose a provider for `cron`. Select `cronie`.<br>
- Press `Apply`<br>
- All KDE Apps will now be downloaded and installed. This can take some time. 
{: .notice--info}

or using a numbered list:

1. `Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`
2. Click on the search icon<br>
3. Type `kde-applications-meta`<br>
4. Click on the `Install` button at the right of `kde-applications-meta`<br>
5. Authorise the operation using the root password<br>
6. **NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>
7. Choose a provider for `cron`. Select `cronie`.<br>
8. Press `Apply`<br>
9. All KDE Apps will now be downloaded and installed. This can take some time. 
{: .notice--info}

or using a blockquote and separate paragraphs :

> `Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`
>
> Click on the search icon<br>
>
> Type `kde-applications-meta`<br>
>
> Click on the `Install` button at the right of `kde-applications-meta`<br>
>
> Authorise the operation using the root password<br>
>
> **NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>
>
> Choose a provider for `cron`. Select `cronie`.<br>
>
> Press `Apply`<br>
>
> All KDE Apps will now be downloaded and installed. This can take some time. 
{: .notice--info}

or<br>
<div class="notice--info" markdown="1">
> `Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`
>
> Click on the search icon<br>
>
> Type `kde-applications-meta`<br>
>
> Click on the `Install` button at the right of `kde-applications-meta`<br>
>
> Authorise the operation using the root password<br>
>
> **NOTE:** if the authorisation request does not come and the system is spending a lot of time in the `Preparing…` mode, restart the system and try again.<br>
>
> Choose a provider for `cron`. Select `cronie`.<br>
>
> Press `Apply`<br>
>
> All KDE Apps will now be downloaded and installed. This can take some time.<br>
</div><br>


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

Now you can add additional apps:

`Application Launcher` -> `Applications` -> `System` -> `Add / Remove Software`
{: .notice--info}

We recommend to install the following:

```
Chromium Web Browser
KDE Partition Manager
exfat-utils
```

Here are some suggestions for additional apps:

```
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

After selecting to install these applications
- Click Apply. 
- The system now asks if you want to install some libraries that are optional for some of these apps. You do not have to select these to get a working app. Only select those options for which you are sure you have a need. Click on Choose.
- Click once more on Apply.

## Final System Configs

## Firefox

Right-click on the Firefox icon in the bottom Task Manager<br>
Unpin from Task Manager<br>
Right-click on the Firefox icon in the Favourites section of the Application Launcher<br>
Remove from Favourites<br>
{: .notice--info}

## Chromium
- Drag the Chromium icon in the Application Launcher into the Task Manager
- Right-click the the Chromium icon in the Application Launcher
    - Add to Favourites
- Chromium Settings -> Make Default Web Browser

## Automatic Login

`Application Launcher` -> `Applications` -> `Settings` -> `System Settings`
Select `Personalization`
Select `Account Details`
Select user `pi`
Enable `Log in automatically`
Provide the `pi` password
{: .notice--info}
