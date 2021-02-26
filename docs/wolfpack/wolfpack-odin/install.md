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

