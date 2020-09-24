---
title: "Raspbery Pi OS Full (32-bit) Installation"
excerpt: "Creating an SSD with the 32-bit version of Raspberry Pi OS including a desktop and recommended applications"
toc: true
---

Since the 64-bit version of the Raspberry Pi OS is not yet fully supported at the time of this writing, we are basing this masterdisk on the 32-bit version of the OS. 
{: .notice--info}


## Create an SSD with Raspberry Pi OS Full (32-bit)

Follow the procedure explained in [Installing Operating System images]({{ "" | relative_url }}../installing-operating-systems/) to create an SSD with Raspberry Pi OS Full (32-bit). This OS does not need to be downloaded beforehand; it can be selected from the main menu in the Raspberry Pi Imager tool after selecting `Raspberry Pi OS (other)`. 

![](/assets/pictures/rpios-32bit-full) 


## Initial Boot Setup

Connect the SSD to the Raspberry Pi using the SSD-to-USB adapter and start the Raspberry Pi.

**Note** The SSD adapter must always be connected to one of the blue USB ports! The blue USB ports are high speed USB 3.0 ports that provide the best performance. The black USB ports are low-speed USB 2.0 ports. If you connect your SSD disk to these low-speed ports, your Raspberry Pi will become very slow. 
{: .notice--warning}


**Note** You start the Raspberry Pi by connecting the power cable to it. But you can never stop the Raspberry Pi by unplugging the power. Doing so might damage the SSD and can make it unusable. Always stop the Raspberry Pi by using the appropriate menu entries for Shutting Down or Restarting the system.
{: .notice--danger}

After the first boot, a setup wizard appears. Provide it the following info:

| Configuration | Value |
| --- | --- |
| Country | Zimbabwe |
| Language | English |
| Timezone | Harare |
| Use English language | x |
| Use US keyboard | x |
| Password for user `pi` | Default password |

Also:
- If you are seeing black border around the desktop, enable `This screen shows a black border around the desktop` 
- Configure a WiFi if needed
- If your are connected to the Internet, select the `Check and Update` option at the end. If no internet connection is available, press `Skip` and update the system at a later time.

Restart the system.

Your SSD now contains a default installation of the Raspberry Pi Operating System.

