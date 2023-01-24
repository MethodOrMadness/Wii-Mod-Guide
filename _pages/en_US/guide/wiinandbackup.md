---
layout: single
title: Making a NAND backup
---

{% include toc title="Table of Contents" %}

Making a NAND backup through BootMii is a very important step. If you accidentally brick your Wii, a NAND backup can help restore it.

## Requirements

- An SD card formatted as FAT32 with at least 512MB of free space

## Procedure

Make sure the SD card you used to install BootMii is inserted in your Wii.

Turn on your Wii. If you installed BootMii as boot2, it will now show up. If so, you can skip the steps in bold.

**Launch the Homebrew Channel, and press the ``HOME`` button on your Wii remote**.

**In the menu that pops up, choose ``Launch BootMii``. BootMii will now load**.

In BootMii, you cannot use a Wii Remote. You must use the physical buttons on the console, or, if your Wii supports it, a GameCube controller.

Press the power button on the Wii to navigate to the gear icon (the 4th option in the list). Press ``RESET`` to enter that menu.

Then, ensure the option with a green arrow is selected, and press ``RESET``.

The NAND backup process will now begin. It may take a while. Leave it. Once it is done, return to the menu, and navigate to the 4th option to return to the main BootMii menu.

Highlight the Wii Menu option (1st option in the list), and press ``RESET`` to boot to the System Menu.

Your NAND backup is now on your SD card. If you would like, you may transfer the files ``nand.bin`` and ``keys.bin`` on the root of your SD card to somewhere safe.

You can now continue to [installing cIOS](/wiicios)
{: .notice--info}
