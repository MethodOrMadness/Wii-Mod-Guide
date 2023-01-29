---
layout: single
title: Installing cIOS
---

{% include toc title="Table of Contents" %}

cIOS is a very important part of Wii softmodding. Its primary function is to allow the playing of backup games, but it does other things as well. This guide will show you how to install cIOS on your Wii.

## Requirements

- An SD card or USB drive formatted as FAT32 (the one you have used previously will work)
- [d2x cIOS Installer](/resources/d2x-cios-installer.zip)
- A way to transfer files to the SD card or USB drive
- A Wii that is connected to the internet

## Preparing d2x cIOS Installer

First, plug the USB drive into whatever you are using to transfer files to it.

Extract the d2x .zip file that you downloaded earlier.

Move the ``apps`` folder to the root of your SD card or USB drive. If you already have one, it will merge the contents.

Eject the SD card or USB drive.

## Installing d2x cIOS

Insert the SD card or USB drive into your console and turn it on.

Next, open the Homebrew Channel on your Wii. There should now be an app named ``d2x cIOS Installer``. Select this app and press ``Load``.

Press ``Continue``. You will then see a screen with options to select. Change the options as follows, or reference the images below:

- ``cIOS: v10 beta52 d2x-v10-b52-ST-FM050``
- ``cIOS base: 57``
- ``cIOS slot: 249``
- ``cIOS version: 65535``

![249](/images/cios/cios249.png)

Once you have verified the settings, press ``A`` twice to install.

When the installation has completed, press ``A`` again to go back to the installer menu.

Change the options again, this time as follows:

- ``cIOS: v10 beta52 d2x-v10-b52-ST-FM050``
- ``cIOS base: 56``
- ``cIOS slot: 250``
- ``cIOS version: 65535``

![250](/images/cios/cios250.png)

Once you have verified the settings, press ``A`` twice to install.

When the installation has completed, press ``A`` again to go back to the installer menu.

Change the options yet again, this time as follows:

- ``cIOS: v10 beta52 d2x-v10-b52-ST-FM050``
- ``cIOS base: 38``
- ``cIOS slot: 251``
- ``cIOS version: 65535``

![251](/images/cios/cios251.png)

Once you have verified the settings, press ``A`` twice to install.

When the installation has completed, press ``B`` to exit.

You are now done installing cIOS on your Wii.

## Errors and how to fix them!

I got an error that says "`net_init failed`"(or similar, such has but not limited to hostname resolution failures) in red!!!! What do i do?

![net_init.failure](/images/cios/net_init.png)

The simplest way to fix that is to connect your wii to the internet or double check network settings, the next simplest is to [download the ios base's](link_to_how_to_here) and copy them to the root of your SD card or USB drive and re-run the installer

---

Congratulations! You have completed the basic steps of softmodding your Wii! At this point, you have a couple options:
{: .notice--success}

(optional, highly recommended) [Backing up and running your games on USB](/wiiusbselectionguide)
{: .notice--info}

Or you may continue to [some things to keep in mind when running homebrew on a Wii](/wiitips)
{: .notice--info}
