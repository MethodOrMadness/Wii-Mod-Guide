---
layout: single
title: WiiFlow
---

{% include toc title="Table of Contents" %}

In this guide, you will be setting up WiiFlow, a simple option for a USB loader that allows you to backup and load games on an external hard drive. Additionally, you can load channels, homebrew apps, and more.

## What you'll need

- An SD card or USB drive formatted as FAT32
- A way to transfer files to your SD card or USB drive
- A USB drive to use for games (this will be referred to in this tutorial as your game drive). If you are not planning to backup GameCube games, format it as NTFS. If you are planning to backup GameCube games, format it as FAT32.
- [WiiFlow](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/wiiflow/WiiFlow%20v4.2.1.zip) (Direct Download)

## Setting up WiiFlow

Plug in your SD card or USB drive into the device you are using to transfer files to it.

Extract the ``WiiFlow.zip`` file that you downloaded earlier. Windows users can simply double click and drag the ``apps`` folder inside to merge or add to your USB drive. Linux or MacOS users must first extract the archive and drag the aforementioned ``apps`` folder to your USB drive to either add it or automatically merge it.

Eject your SD card or USB drive, and remove it once prompted by your operating system.

Insert your SD card into your Wii, or if you are using a USB drive, plug it into the USB port that is furthest away from the edge.

Plug in your game drive into the USB port that is closest to the edge.

On your Wii, open the Homebrew Channel, and launch WiiFlow. Once you launch it, you should see the WiiFlow splash-screen, followed by a loading screen. You will be brought to a screen that says "Hello! I am WiiFlow. I have not found any games. Choose from the options below."

WiiFlow is now ready for use.

## Backing up games to your game drive

Backing up Wii games is relatively simple in any USB loader. Once in WiiFlow, simply click the ``Install Game`` button at the games not found prompt. Choose ``USB1``. It will begin ripping the inserted disc to your game drive.

## Downloading covers (requires internet connection)

WiiFlow will show you covers once you have downloaded them, but before that, you will be shown a big white ``?`` on the cover of each game. We can fix that.

Press the home button. Then, click ``Settings`` The ``Download Covers`` option is the first one. You will have many choices for customization. If you want only stock covers for your console's region, then just click ``Go`` without changing anything. If you want to spice it up, then you can set the preferred covers to ``Custom``. Or, you can change the region as desired.

You'll need the Internet for this process.

You are done with WiiFlow.

You can now continue on to [some things to keep in mind when running homebrew on the Wii](/wiitips)
{: .notice--info}
