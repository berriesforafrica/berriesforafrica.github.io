---
title: "Installing Offline Wikipedia"
excerpt: "Procedure to install Wikipedia and related content for offline use"
toc: true
---



**Note:** No Internet connection is required to follow the procedure below. 
{: .notice--info}

Connect an SSD containing the offline Wikipedia content. 

**Note:** Do not disconnect the Manjaro KDE SSD. Doing so will freeze your system.
{: .notice--warning}

Open the Dolphine file browsing app (`Application Launcher` -> `Applications` -> `System` -> `Dolphin`).

Select the SSD with the Wikipedia content (for example `WIKIPEDIA`). Verify that the SSD with the Wikipedia content is mounted and accessible.

Now open the Konsole app (`Application Launcher` -> `Applications` -> `System` -> `Konsole`) and execute the following commands:

```
sudo cp /run/media/pi/WIKIPEDIA/kiwix-tools.linux-armhf.3.1.2-3/* /usr/local/bin/
sudo cp /run/media/pi/WIKIPEDIA/*.zim /var/local/
```

**Note:** If for some reason you need to update the Kiwix executables, connect you Raspberry Pi to the Internet and follow the intial steps explained [here](https://www.rickmakes.com/offline-wikipedia-on-wired-raspberry-pi-using-kiwix/) to download and install the latest version of the Kiwix tools. 
{: .notice--info}

Both the content and the tools to display the content are now installed. Lets create the menu entries to start the concent server and content browser.

Right-click the `Application Launcher` and select `Edit Applications`.

Select `Education` -> `Miscellaneous` -> `New Item...`.

Provide the following info:

| Name | Start Wikipedia |
| Description | Start the server that provides offline access to Wikipedia and related content |
| Comment | Start the server that provides offline access to Wikipedia and related content |
| Command | `echo "THIS IS THE WIKIPEDIA SERVER. CLOSE THIS WINDOW TO STOP THE SERVER." kiwix-serve /var/local/*.zim -p 8012` | 

Click `Advanced`.

Enable `Run in terminal`.

Now click on the `Save` button at the top left of the panel.

We have created a menu entry for starting the Wikipedia server. Now we are going to follow a similar procedure to add a menu entry for starting the Wikpedia browser.

Select `Education` -> `Miscellaneous` -> `New Item...`.

Provide the following info:

| Name | Browse Wikipedia |
| Description | Browse Wikipedia content and related content without an Internet connection |
| Comment | Browse Wikipedia content and related content without an Internet connection |
| Command | `chromium http://localhost:8012` | 

Now click on the `Save` button at the top left of the panel.

Now you can start using the offline wikipedia. Two steps are reauired to do so:

1. Start the Wikipedia Server using `Application Launcher` -> `Applications` -> `Education` -> `Start Wikipedia`.
2. Open the Wikipedia Browser using `Application Launcher` -> `Applications` -> `Education` -> `Browse Wikipedia`.

**Note:** You can also browse the Wikipedia content by opening the browser of your choice and using the following URL: `http://localhost:8012`. 

