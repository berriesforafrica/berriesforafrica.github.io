---
title: "Style Guide"
excerpt: "Style guide for entering content on this site"
toc: true 
---


## Visualising Installation Steps

Lets explore different ways to visualise installation steps and motivate our final choice at the end. 

### Using `<br>` 

Right-click on the Firefox icon in the bottom Task Manager<br>
Unpin from Task Manager<br>
Right-click on the Firefox icon in the Favourites section of the Application Launcher<br>
Remove from Favourites<br>
{: .notice--info}

This is not OK as the different steps are not very well separated.

### Using a bullet list

- Right-click on the Firefox icon in the bottom Task Manager
- Unpin from Task Manager
- Right-click on the Firefox icon in the Favourites section of the Application Launcher
- Remove from Favourites
{: .notice--info}

Separation is OK, but visually this is not very attractive.

### Using a numbered list

1. Right-click on the Firefox icon in the bottom Task Manager
1. Unpin from Task Manager
1. Right-click on the Firefox icon in the Favourites section of the Application Launcher
1. Remove from Favourites
{: .notice--info}

Better, but not perfect as the numbers do not stand out.

### Using `<br>` and a bold prefix

**1.** Right-click on the Firefox icon in the bottom Task Manager<br>
**2.** Unpin from Task Manager<br>
**3.** Right-click on the Firefox icon in the Favourites section of the Application Launcher<br>
**4.** Remove from Favourites<br>
{: .notice--info}

or

**Step1.** Right-click on the Firefox icon in the bottom Task Manager<br>
**Step2.** Unpin from Task Manager<br>
**Step3.** Right-click on the Firefox icon in the Favourites section of the Application Launcher<br>
**Step4.** Remove from Favourites<br>
{: .notice--info}

Better, but not perfect as we have removed the space between steps. 

### Using paragraphs inside a `<div>` 

<div class='notice--info' markdown=1>
**Step1.** Right-click on the Firefox icon in the bottom Task Manager

**Step2.** Unpin from Task Manager

**Step3.** Right-click on the Firefox icon in the Favourites section of the Application Launcher

**Step4.** Remove from Favourites
</div>

Perfect!