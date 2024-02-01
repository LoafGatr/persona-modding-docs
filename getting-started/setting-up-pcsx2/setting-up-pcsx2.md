---
title: Setting up PCSX2
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

{: .todo }
> This only applies for P3FES USA ISO file. And needs some testing for P4 (Vanilla)

{: .info }
> Ensure that you have PCSX2 Version **1.6.0** otherwise, this guide will not work.

# Phase 1 - First Time Configuration

## Tools You'll Need
- [PCSX2 - 1.6.0](https://pcsx2.net/)

## Files you will need
- PS2 BIOS - You will have to get it through a physical PS2, follow this guide from [P3F Community Enchancement Pack Guide](https://p3f.cep.one/install/dump-ps2-bios)
- P3FES rom - **You will have to find that rom for yourself.**

{: .todo }
> To dos
> Set up bios > Get Rom > Set up HostFS > Download necessary Pnach files for testing* (Might need to see if this necessary as a separate page)

## Set up
After installing PCSX2 this window will appear.

![]({%link assets/images/getting-started/setting-up-PCSX2/Setting-up-PCSX2-First-Time-Configuration.png %})

Click **Next**.

The next page should be about plugins, we don't need to configure any of this so click **Next**.

![]({%link assets/images/getting-started/setting-up-PCSX2/Setting-up-PCSX2-First-Time-Configuration-Plugins.png %})

## Selecting Bios
{: .info }
> This portion already assumes you have obtained a ``PS2 BIOS``. If you haven't, please follow this guide from [P3F Community Enchancement Pack Guide](https://p3f.cep.one/install/dump-ps2-bios)

This window should be empty if you just installed PCSX2:
![]({%link assets/images/getting-started/setting-up-PCSX2/Setting-up-PCSX2-Selecting-BIOS.png %})

The default BIOS directory will be under ``...\Documents\PCSX2\bios``, this is where we will be placing the ``PS2 BIOS``.
For a quick access to the folder, Click **Open in Explorer**. This will open the file explorer to ``...\Documents\PCSX2\bios``.

From there move your ``PS2 BIOS`` to the bios directory. The BIOS directory should look something like this:

![]({%link assets/images/getting-started/setting-up-PCSX2/Setting-up-PCSX2-Placing-Bios.png %})

Once you placed the ``PS2 BIOS`` into the bios directory, return to the PCSX2 First Time Configuration Window. Under the *Select a BIOS rom:* section, click **Refresh list**. There will now be an item on the Select a BIOS rom list.
![]({%link assets/images/getting-started/setting-up-PCSX2/Setting-up-PCSX2-Bios-on-the-list.png%})

{: .info }
> Make sure to select the bios if you haven't done so already!

Now click **Finish**.

If everything work as intended

---

# Phase 2 - Changing configurations & Loading Roms

## Loading rom

{: .info }
> You need to obtain P3FES ROM **on your own**. If you happen have a physical copy of P3FES, please follow this guide from 

Congratulation! You finally got PCSX2 set up! Now that last thing we need to do is load up P3FES to make sure that the set up work as intended.




