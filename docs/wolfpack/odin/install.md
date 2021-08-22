---
title: Wolfpack Odin (Installation)
sidebar_label: Install
---

The installation process is surprisingly simple, in theory. This part is the most experimental, so should any issues arise, feel free to let me know.

:::caution
It is imperative that you have [Java](/docs/pre-install/java) and [MultiMC](/docs/pre-install/multimc) installed before performing this step.
:::

### Installing the modpack

1. Click **Add Instance** on MultiMC.
2. There will be an option to **Import from zip**, select that and paste the following URL into the field: `https://get.kalka.io/Wolfpack-Odin`
3. Hit OK, and allow the modpack to fully download its requisites, which shouldn't take too long depending on your internet connection.

Once imported, you may feel free to double-click the instance and allow the requisites to download. This is usually where most setups would fail, but any easy troubleshooting can be done at the request.

:::info
For Linux/macOS users: If you are not using Windows as your main operating system, you will need to **Edit Instance**, select **Settings** and replace the beginning part of `update.bat` on the **Pre-launch command** to be something like `python3 update.py` or whatever Python 3 is set to as your $PATH.
:::

### A Disclaimer About OptiFine

In recent versions, this modpack has been tested with **OptiFine_1.16.5_HD_U_G8**. Visually, it seems to have some FPS improvements, but there are a number of reasons why the mod is not included by default:
- OptiFine increases the modpack load time by about a 30% margin (To put that to scale, in general, without OptiFine loaded, the modpack loads in 2 minutes. After installing OptiFine, the modpack load time is increased to **5 minutes.**)
- It tends to have visual conflicts with some mods

One of the pros I can say about OptiFine is that it does stabilize FPS quite some, but the cost of waiting longer for better performance is a gray area I'd rather not mess with in terms of the main upstream of the modpack. If you want to add it, by all means, but I will not offer support on a modpack that has OptiFine installed.


