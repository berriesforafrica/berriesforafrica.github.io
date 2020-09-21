---
title: "BACKUP Manjaro KDE - Apps - Wiki"
excerpt: "Creating an SSD with Manjaro KDE, all KDE Applications and Offline Wikipedia content"
toc: true
---

### Install the Manajaro KDE Operating System on an SSD

Follow the instructions in [Manjaro KDE - Full Apps]({{ "" | relative_url }}../manjaro-kde/) to create an SSD with Manjaro KDE and a suite of Applications.

**Note:** You can leave out any of the Applications in these instructions if you do not need them.
{: .notice--warning}


### Offline Wikipedia Setup

Install the following applications (see [Installing Applications]() for more information on how to install applications in Manjaro KDE).

```
snapd with extra xdg-desktop-portal option (select xdg-desktop-portal-kde)
```

Restart the system - TBD; other doc reference on instruction copy or nothing?

Open a terminal and execute the following command:

```
$pi> sudo snap install kiwix-tools --edge 
$pi> kiwix-tools.kiwix-serve *.zim -p 8012
```

Add an application menu entry for Kiwix Server:

| Name | `Start Kiwix Sefver` |
| Description | `Open Kiwix Browser` |
| Command | `cd ~/Documents;echo "KIWIX SERVER - CLOSE THIS WINDOW TO STOP THE SERVER";kiwix-tools.kiwix-serve *.zim -p 8012` |
| Advanced options | `` | 

Add application menu entry for Kiwix Browser

| Name | `Open Kiwix Browser` |
| Description | `Open Kiwix Browser` |
| Command | `Open Kiwix Browser` |

Now add the Kiwix content files:

- Connect the Wikipedia SSD
- **Note:** Do not disconnect the Manjaro KDE Disk. Doing so will freeze your system.
{: .notice--warning}
- Copy the required offline content to /home/pi/Documents

Now you can start using the offline wikipedia browser. Two steps aqre reauired to do so:

1. Open the Offline Wikipedia Server by 
2. Open the Offline Wikipedia Browser

Note that 


- EXTRA 
    - KDE Partition Manager
    - kiwix
        - install exfat-fuse and exfat-utils
        - install snapd
            - with extra xdg-desktop-portal option (select xdg-desktop-portal-kde)
        reboot
        sudo snap install kiwix-tools --edge 
        kiwix-tools.kiwix-serve *.zim -p 8012
        - add application menu entry for Kiwix Server
            - Name
                - Start Kiwix Server
            - Description
                - Offline Wikipedia Server
            - Command
            cd ~/Documents;echo "KIWIX SERVER - CLOSE THIS WINDOW TO STOP THE SERVER";kiwix-tools.kiwix-serve *.zim -p 8012
            - advanced options
                - run in terminal
        - add application menu entry for Kiwix Browser
            - Name
                - Open Kiwix Browser
            - Description
                - Open Kiwix Browser
            - Command
                - Open Kiwix Browser


