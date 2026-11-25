# HyperMods

Native Bitwig Studio devices, published for [Patchbay Launcher](https://github.com/arius77R/patchbay-launcher).

**Beta.** HyperBlur has not been tested in a running Bitwig Studio yet.

| Device | Type | What it does |
| --- | --- | --- |
| [HyperBlur](Bitwig-6.1.7/HyperBlur.bwdevice) | Audio FX | A centred blur with Gaussian, Kawase, Disc and Bokeh kernels and feedback, ported from the HyperBlur plug-in. This build has no sidechain yet, so its Signal Kernel model passes the dry signal. |

## Install

In Patchbay Launcher: **Sources**, the **Devices** tab, **+ Add**, type `roguefort-dev/HyperMods` and click **Check**. HyperBlur is then under **Devices**: tick it and click **Download ticked**.

By hand: in Patchbay's window, add this repository's `Bitwig-6.1.7` folder under **Tools > Device Folders**.

The device is for Bitwig Studio 6.1.7 and later. Its output is always 4098 samples late, and it declares that delay.
