# Welcome to the Z80 Retro! project repository collection!

The purpose of this organization is to provide an easy way to locate the repositories of hardware and software projects for the Z80 Retro!

The Z80 Retro! project is presented on the John's Basement channel on YouTube.  A [Z80 Retro! playlist](https://www.youtube.com/playlist?list=PL3by7evD3F51Cf9QnsAEdgSQ4cz7HQZX5) contains much detail about all aspects of this project including the circuit boards, CP/M, the BIOS, and a video display board that uses a popular Video Display Processor called the TMS9118.

## Pre-Compiled Binaries 

There are pre-compiled binaries of the boot ROM flash and SD card image for the Z80 Retro! in a zip file that is part of [the latest official software release in github here](https://github.com/Z80-Retro/2063-Z80-cpm/releases/latest).

## PC Boards

The bare PC boards can be ordered directly from manufacturers for under $30 USD by using the `XXX-gerbers.zip` files that appear in the latest release of the respective repos.  See the section below named [Hardware Project Repos](https://github.com/Z80-Retro#hardware-project-repos).  I have been ordering bare Retro! boards from JLCPCB and get 5 of each (15 total PCBs) for about $30 USD.  [There is a video on how to order them directly from JLCPCB or OSHPark here](https://youtu.be/AUg_sbPnzn0).

## Version Tags and the YouTube Video Series

As of 20220304, in order to locate the exact same versions of the source code as seen in the playlist you can check out (or download) the specific version of the code using the date-code seen at the start of each video (that look like this: YYYYMMDD.n) 

For each repo in the Z80-Retro github organization, you will find a *git tag* with the same date-code in it that matches the given videos that are focused on that repo.  (Click on the tags link in any given repo to see them all.)

## Where to Find Everything


### Documentation and Manuals:
- [Z80-Retro-Manual](https://github.com/Z80-Retro/Z80-Retro-Manual) - The official Z80-Retro! manual
- [3rd Party Manuals](https://github.com/Z80-Retro/manuals) - Manuals for CP/M, books, chips, and other stuff
- Watch the videos in the [Z80 Retro! playlist](https://www.youtube.com/playlist?list=PL3by7evD3F51Cf9QnsAEdgSQ4cz7HQZX5). Everything about the schematic, PCB design, downloading & assembling the software, programming the boot-FLASH and SD cards, and CP/M software are covered in great detail.  If anything was missed, feel free to comment on YouTube or the [discord](https://discord.gg/jf73DRZvh5).  Your voice will be heard.


### Hardware Project Repos:
- [2063-Z80](https://github.com/Z80-Retro/2063-Z80) - The Z80 CPU board [Latest release](https://github.com/Z80-Retro/2063-Z80/releases/latest)
- [2065-Z80-programmer](https://github.com/Z80-Retro/2065-Z80-programmer) - A Raspberry PI based board that can program the Z80 Retro FLASH in-circuit. [Latest release](https://github.com/Z80-Retro/2065-Z80-programmer/releases/latest)
- [3D Printable PCB Standoffs ](https://github.com/Z80-Retro/pcb-standoffs) For the VDP and FLASH programmer boards.
- [2068-Z80-TMS9118](https://github.com/Z80-Retro/2068-Z80-TMS9118) - A Video Display Processor board with composite video output. [Latest release](https://github.com/Z80-Retro/2068-Z80-TMS9118/releases/latest)
- [You can order your own bare PCBs directly from JLCPCB or OSHPark](https://youtu.be/AUg_sbPnzn0) by using the XXX-gerbers.zip files in the latest releases. Note that ordering from PCBWay is VERY similar to JLCPCB if you want to shop around.

### Software Project Repos:
- [2063-Z80-cpm](https://github.com/Z80-Retro/2063-Z80-cpm) - The boot ROM, BIOS, and filesystem suitable for basic operation of the Z80 CPU board. See the [latest releases for binaries in the zip-file asset](https://github.com/Z80-Retro/2063-Z80-cpm/releases/latest).
- [example-filesystem](https://github.com/Z80-Retro/example-filesystem) - An example filesystem suitable for developing example/test applications.
- [Games](https://github.com/Z80-Retro/acn-vt100-games) and build script to copy them into a Retro SD card from Anna Christina Naß's repo here: https://git.imzadi.de/acn/vt100-games
- [Z80-Retro-disk-maker](https://github.com/Z80-Retro/Z80-Retro-disk-maker) - an example Makefile etc. for building a filesystem.  See the Anna Christina Naß's games repo (above) for an example of how to use it.
- [CPM3_2063_Retro](https://gitlab.com/SolderGirl/CPM3_2063_Retro) - A port of CP/M 3 to the Retro! by SolderGirl
 
## Links to related social media:
- The [Z80 Retro! YouTube playlist](https://www.youtube.com/playlist?list=PL3by7evD3F51Cf9QnsAEdgSQ4cz7HQZX5)
- The [Z80 Retro! Discord permanant invitation link](https://discord.gg/jf73DRZvh5)
- The [John's Basement](http://youtube.com/@JohnsBasement) YouTube channel that hosts the Z80 Retro! playlist.
- NOTE: The original home of the Z80 Retro project repos has been under the [John Winans](https://github.com/johnwinans) github account.  He, later, moved it here.
