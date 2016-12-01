---
layout: post
title:  Some updates on STM32Tool
---

This summer I released [STM32Tool](https://github.com/gdelazzari/STM32Tool) to the public.

If you don't know what I'm talking about, you should check out the project page linked above. By the way, in a few words

> This is a CLI (Command Line Interface) tool that helps during the development process of STM32 firmware projects. It reduces the hassle of configuring a new project, installing CMSIS and the new ST HAL libraries as well as configuring the linker script, startup files, etc...

There were no commits since then, but that doesn't mean the project is abandoned. It just means that, in the current state, with the feature it has, it's perfectly working and serving me well.

I will continue for sure the project, to follow my dream of an Atom-based STM32 IDE, with the aim to replace all these Eclipse ones. In the meantime, some small updates will come for sure, like the Python 3 support, an automatic HAL libs updating feature and other small changes.

I'll also start working on multiple project templates (i.e. supporting the old SPLs or creating barebones projects) and I recently noticed the [mbed OS 5](https://developer.mbed.org/), which is amazing for simple, quick and dirty projects thanks to it's *"good"* amount of libraries available (while still offering an RTOS working base). Integrating the mbed CLI with STM32Tool would be a nice move, so in a future IDE it will be possible to instantly create mbed OS projects with a few clicks.

By now, if you're using the HAL libraries or if you want to learn the STM32 platform (in that case you may start with them), you should check out this tool. Feedback is also really appreciated.
