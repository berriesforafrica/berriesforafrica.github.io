---
title: "Manjaro KDE Installation"
excerpt: "Creating an SSD with Manjaro KDE"
toc: true
#order: 002
#date: 2020-09-20
---

## Create an SSD with the Manajaro KDE Operating System 



To create an SSD with the latest version of Manjaro KDE for Raspberry Pi, perform the following steps:

<div class='notice--info' markdown='1'>
**Step1:** Download the latest version of Manjaro KDE for Raspberry Pi from [here](https://manjaro.org/download/#raspberry-pi-4-kde-plasma).

**Step2** Decompress and install the image on an SSD as explained in [Installing Operating System images]({{ "" | relative_url }}../installing-operating-systems/).
</div>


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

<div class="notice--info" markdown="1">
**Step1:**  `Application Launcher` -> `Applications` -> `System` -> `Software Update`

**Step2:** Press `Apply`

**Step3:** Provide root password

**Step4:** Press `Apply`
</div>


Reboot (= restart) the system by clicking on `Application Launcher` -> `Leave` -> `Restart`

Your SSD now contains a default installation of the Manjaro KDE Operating System.
