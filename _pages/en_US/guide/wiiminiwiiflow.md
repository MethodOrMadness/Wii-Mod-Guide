---
layout: single
title: WiiFlow
---

In this guide, you will be setting up WiiFlow, a simple option for a USB loader that allows you to backup and load games on an external hard drive. Additionally, you can load channels, homebrew apps, and more.

*If you are using a USB hub, then all italicized text is specifically for you.*

**If you are NOT using a USB hub, then all bolded text is specifically for you.**

## What you'll need

- A USB drive formatted as FAT32, *NTFS, exFAT, or FAT16.* **If you don't have a USB hub, then you will need to use the same drive that you use to load games, forcing you to use FAT32.** *If you are using a USB hub, then you can use any format you want, as you do not need to use the same drive for homebrew apps as you do for games.*
- A Wii Mini with cIOS installed.
- A way to transfer files to your USB device
- [WiiFlow](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/wiiflow/WiiFlow%20v4.2.1.zip) (Direct Download)

## Setting up WiiFlow

**Plug in your USB drive to whatever device you are using to transfer files.**

*Plug in your USB drive designated for apps into your device used to transfer files.*

Extract the WiiFlow.zip file that you downloaded earlier. Windows users can simply double click and drag the ``apps`` folder inside to merge or add to your USB drive. Linux or MacOS users must first extract the archive and drag the aforementioned ``apps`` folder to your USB drive to either add it or automatically merge it.

Eject your USB drive, and remove it once prompted by your operating system.

**Plug your USB drive into the back of your Wii Mini**

*Plug your USB hub into your WIi Mini, and then plug both your games and apps USB drives into your USB hub.*

On your Wii Mini, open the Homebrew Channel, and launch WiiFlow. Once you launch it, you should see the WiiFlow splash-screen, followed by a loading screen. You will be brought to a screen that says "Hello! I am WiiFlow. I have not found any games. Choose from the options below."

WiiFlow is now ready for use.

## Backing up games to your USB drive

Backing up Wii games is relatively simple in any USB loader. Once in WiiFlow, simply click the ``Install Game`` button at the games not found prompt. Choose ``USB``. It will begin ripping the inserted disc to your USB drive.

*Before ripping games, be sure you have chosen the right drive. Insert both of your USB drives in order, leaving no USB drive in-between. Choose ``USB1`` if your games drive is inserted first. Choose ``USB2`` if your games device is inserted second.*

## Downloading covers (requires USB hub)

WiiFlow will show you covers once you have downloaded them, but before that, you will be shown a big white ``?`` on the cover of each game. We can fix that.

Press the home button. Then, click ``Settings`` The ``Download Covers`` option is the first one. You will have many choices for customization. If you want only stock covers for your console's region, then just click ``Go`` without changing anything. If you want to spice it up, then you can set the preferred covers to ``Custom``. Or, you can change the region as desired.

You'll need the Internet for this process, something that can only be done with a USB ethernet adapter, and thus can't be done with no USB hub.

You are done with WiiFlow.

You can now continue on to [some things to keep in mind when running homebrew on the Wii Mini](/wiiminitips)
{: .notice--info}
