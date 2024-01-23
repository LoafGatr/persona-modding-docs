---
title: Extracting The Game's Files P3F
layout: page
parent: Getting Started
nav_order: 1
games: ['P3F']
---

Before you start making your mod you'll need to extract the game's base files so you can find what you actually want to edit. 

## Extracting ISO
All of the game's files are stored in an ISO file which in turn contains CVM files such as `DATA.CVM` and `BGM.CVM`.

To unpack these you'll need to download [7Zip](https://www.7-zip.org/).

{: .warning }
> 7Zip only works with Windows machines. 

Now go to your P3F ISO file, select it, and right click, there should now be "7Zip" on the top menu.

Go to 7Zip > Extract to P3F ISO (or whatever the name of your ISO ROM file is named)\

![]({%link assets/images/getting-started/Unpacking-P3F-USA-ISO.png %})

This will create a new directory under the name of the P3F ISO file. It should look something like this:

Inside will contain the follow files:
- `LIB31` - Folder
- `BGM.CVM` - BGM files
- `BTL.CVM` - Battle and model related files
- `DATA.CVM` - Main Files
- `SLUS_216.21` - The game itself.

It's recommended to dump the main files (aka `DATA`) to start with since it contain things like `events`, `sound`, and `field`

## Extracting CVM Files
Similar to how the P3F ISO file got extracted, it's the same process for when you extract **CVM** files.

Select `DATA.CVM`, right click on the file and from the top menu > 7Zip > Extract to "DATA"

![]({%link assets/images/getting-started/files-in-P3F-USA-ISO.png %})