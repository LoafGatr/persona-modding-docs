---
title: Setting up PCX2
layout: page
parent: Setting up PCX2
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

{: .todo }
> This only applies for P3FES USA ISO file. And needs some testing for P4 (Vanilla)

{: .info }
> Ensure that you have PCX2 Version **1.6.0** otherwise, this guide will not work.

## Tools You'll Need
- [PCX2 - 1.6.0](https://pcsx2.net/)

## Files you will need
- PS2 BIOS - You will have to get it through a physical PS2, follow this guide from [P3F Community Enchancement Pack Guide](https://p3f.cep.one/install/dump-ps2-bios)
- P3FES rom - **You will have to find that rom for yourself.**

{: .todo }
> To dos
> Set up bios > Get Rom > Set up HostFS > Download necessary Pnach files for testing* (Might need to see if this necessary as a separate page)

## Set up Bios

## Load Rom


## Getting HostFs
- Getting Hostfs can be found through this [ShrineFox's website](https://shrinefox.com/GetStarted)

Under Game Platform, click on the dropdown and select ``Playstation 2``

![]({%link assets/images/getting-started/setting-up-PCX2/Getting-Hostfs-Through-ShrineFox-Game-Platform-Selection.PNG %})

Game Title section should appear afterwards with the default option being ``Persona 3 FES``

![]({%link assets/images/getting-started/setting-up-PCX2/Getting-Hostfs-Through-ShrineFox-Game-Title.PNG %})

On the *Game Title* section click **Next**. 

This will reveal the *Game Region* section.

![]({%link assets/images/getting-started/setting-up-PCX2/Getting-Hostfs-Through-ShrineFox-Game-Region.PNG %})

Currently, there is only one option available which is **USA**. There's nothing to change for this option so click **Next**.

If you followed the steps so far, this is what your page should look like:

![]({%link assets/images/getting-started/setting-up-PCX2/Getting-Started-Selected-P3FES-USA.png %})

Since we're using **an emulator**, we need to change the target platform from ``Console`` to ``Emulator``.

![]({%link assets/images/getting-started/setting-up-PCX2/Getting-Started-Targeted-Platform-Then-Next.png %})

After selecting ``Emulator``, click **Next**.

Scroll down until you Patches section. There should be a list of check boxes with three already checked off for you: ``HostFS``, ``Direct Commands``, and ``Debug Log``

![]({%link assets/images/getting-started/setting-up-PCX2/Getting-HostFs-Patches.png %})

You can uncheck ``Direct Commands`` and ``Debug Log`` if you wish. What is needed is ``HostFs`` which is checked by default and **cannot** be unchecked.

From there click **Download PNACH** and download the file.

It is recommended to add the name of what patches you have selected at the end of the file such as ``94A82AAA_HostFs.pnach``.

{: .info}
> Create a folder where you can save these ``PNACH`` files. That way, if you want to download other ``PNACH`` files you can save them without having to download them again.