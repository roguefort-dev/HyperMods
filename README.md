# HyperMods

Native Bitwig Studio devices, published for [Patchbay Launcher](https://github.com/arius77R/patchbay-launcher).

| Device | Type | What it does |
| --- | --- | --- |
| [HyperBlur](Bitwig-6.1.7/HyperBlur.bwdevice) | Audio FX | Centred blur with up to 256 weighted taps, a five-second Radius, tap randomization and inversion, and a native FB FX chain. |

HyperBlur offers Standard, Zero Latency, and No Pre Taps modes. Mix defaults to
100% wet. Internal feedback returns on the next sample. Devices in FB FX use
Bitwig's native feedback bridge.

## Install

In Patchbay Launcher: **Sources**, the **Devices** tab, **+ Add**, type `roguefort-dev/HyperMods` and click **Check**. HyperBlur is then under **Devices**: tick it and click **Download ticked**.

By hand: in Patchbay's window, add this repository's `Bitwig-6.1.7` folder under **Tools > Device Folders**.

The device is for Bitwig Studio 6.1.7 and later. Reinsert HyperBlur in an existing project to load a new build.
