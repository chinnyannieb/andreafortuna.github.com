---
layout: post
title: "Shutting down computer on USB port activity? Yes, with USBKill"
description: "USBKill, a simple console tool to shutdown computer on USB port activity"
thumbnail: "http://www.andreafortuna.org/technology/images/usbkill.PNG"
category: Security
tags: 
- Unix
- Linux
- OSX
- USB
- USBKill
- Security

---
{% include JB/setup %}
*USBkill* is a simple console tool that waits for a change on your USB ports and then immediately shuts down your computer.

![USBKILL](http://www.andreafortuna.org/technology/images/USBKill.gif)
<!-- more -->

From [GitHub repository](https://github.com/hephaest0s/usbkill){:target="_blank"}:

>Why?
Some reasons to use this tool:

>- In case the police or other thugs come busting in (or steal your laptop from you when you are at a public library as happened to Ross). The police commonly uses a « mouse jiggler » to keep the screensaver and sleep mode from activating.
>- You don’t want someone retrieve documents (such as private keys) from your computer or install malware/backdoors via USB.
>- You want to improve the security of your (Full Disk Encrypted) home or corporate server (e.g. Your Raspberry).
[!] Important: Make sure to use (partial) disk encryption! Otherwise they will get in anyway.

>Tip: Additionally, you may use a cord to attach a USB key to your wrist. Then insert the key into your computer and start usbkill. If they steal your computer, the USB will be removed and the computer shuts down immediately.

Slightly paranoid!

Anyway, the tool is useful also as a simple security system in case of theft of laptop: with a simple USB key connected to a security cable tied to the desk. :-)

I had already spoken in a previous [Weekly Roundup](http://www.andreafortuna.org/weeklyroundup/2015/05/11/weekly-roundup-23/): latest updates, however, are quite remarkable:

>(version 1.0-rc.2)
>- Compatible with Linux, *BSD and OS X.

>- Shutdown the computer when there is USB activity.
- Customizable. Define which commands should be executed just before shut down.
- Ability to whitelist a USB device.
- Ability to change the check interval (default: 250ms).
- Ability to melt the program on shut down.
- Works with sleep mode (OS X).
- No dependency except srm. sudo apt-get install secure-delete
- Sensible defaults


*[Download from GitHub](https://github.com/hephaest0s/usbkill){:target="_blank"}*
