---
title: Setting up HostFs
layout: page
parent: Setting up PCSX2
grand_parent: Getting Started
nav_order: 1
games: ['P3F']
---

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Getting HostFs
- Getting Hostfs can be found through this [ShrineFox's website](https://shrinefox.com/GetStarted)

Under Game Platform, click on the dropdown and select ``Playstation 2``

![]({%link assets/images/getting-started/setting-up-hostfs/Getting-Hostfs-Through-ShrineFox-Game-Platform-Selection.PNG %})

Game Title section should appear afterwards with the default option being ``Persona 3 FES``

![]({%link assets/images/getting-started/setting-up-hostfs/Getting-Hostfs-Through-ShrineFox-Game-Title.PNG %})

On the *Game Title* section click **Next**. 

This will reveal the *Game Region* section.

![]({%link assets/images/getting-started/setting-up-hostfs/Getting-Hostfs-Through-ShrineFox-Game-Region.PNG %})

Currently, there is only one option available which is **USA**. There's nothing to change for this option so click **Next**.

If you followed the steps so far, this is what your page should look like:

![]({%link assets/images/getting-started/setting-up-hostfs/Getting-Started-Selected-P3FES-USA.png %})

Since we're using **an emulator**, we need to change the target platform from ``Console`` to ``Emulator``.

![]({%link assets/images/getting-started/setting-up-hostfs/Getting-Started-Targeted-Platform-Then-Next.png %})

After selecting ``Emulator``, click **Next**.

Scroll down until you Patches section. There should be a list of check boxes with three already checked off for you: ``HostFS``, ``Direct Commands``, and ``Debug Log``

![]({%link assets/images/getting-started/setting-up-hostfs/Getting-HostFs-Patches.png %})

You can uncheck ``Direct Commands`` and ``Debug Log`` if you wish. What is needed is ``HostFs`` which is checked by default and **cannot** be unchecked.

From there click **Download PNACH** and download the file.

It is recommended to add the name of what patches you have selected at the end of the file such as ``94A82AAA_HostFs.pnach``.

{: .info}
> Create a folder where you can save these ``PNACH`` files. That way, if you want to download other ``PNACH`` files you can save them without having to download them again.


(After PCX2 is set up) > Backport P4 fields > How to Backport a simple P4 events > Debugging Models > Hex Edit > How to replace and or add BGM > How to Alter PM2 files
 