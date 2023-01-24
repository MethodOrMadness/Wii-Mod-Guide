---
layout: single
title: Executing Bluebomb
---

{% include toc title="Table of Contents" %}

If you run into trouble at this point, we recommend that you join the [Wii Mini Hacking Discord server](https://discord.gg/zyPKqt4) for support.
{: .notice--warning}

### Preparing your console

Before you can run Bluebomb, you need to prepare your Wii Mini to run it. This is very simple to do.

First, plug your USB drive containing the HackMii Installer into your console. The USB port is on the back.

Next, turn on your console. Leave it on the Health and Safety screen. Do not connect any Wii Remotes. If you connect a Wii Remote by mistake, either restart the console or remove the batteries from the remote.

You can now continue to the next section.

### Running the exploit

First, open up a terminal in your Linux environment. This varies depending on what distro you are using, but on Ubuntu and many others, you can open a terminal simply by using the key combination ``CTRL+Alt+T``

Next, input the following commands, one by one, in order.

    wget https://guide.rwiihacks.com/assets/files/bluebomb-helper.sh --no-check-certificate
    
    chmod +x bluebomb-helper.sh
    
    ./bluebomb-helper.sh

At this point, you will see the Bluebomb Helper begin. First, it will download Bluebomb. Then, it will ask you a series of questions.

The first thing it will ask is what console you are using. Choose ``Wii Mini`` and continue.

Next, it will ask you what region your Wii Mini is. Select ``NTSC``.

Finally, it will ask you to confirm your choices. Confirm it, and then Bluebomb will begin.

The console will now show a series of different screens, until finally, it will display the HackMii Installer scam screen.

Once your console boots to the scam screen, you no longer need your Linux environment.

---

[Continue to the HackMii Installer](/wiiminihackmii)
{: .notice--info}
