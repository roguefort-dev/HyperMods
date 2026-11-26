# HyperMods

Native Bitwig Studio devices, published for [Patchbay Launcher](https://github.com/arius77R/patchbay-launcher).

**Beta.** The first build of HyperBlur loads in Bitwig Studio 6.1.7 and its panel shows there. This build is new: a latency that follows the kernel, a radius to 500 ms and, with ×10, to 5 s, a narrower panel. It has not been loaded in Bitwig yet.

| Device | Type | What it does |
| --- | --- | --- |
| [HyperBlur](Bitwig-6.1.7/HyperBlur.bwdevice) | Audio FX | A centred blur with Gaussian, Kawase, Disc and Bokeh kernels and feedback, with a preview of the kernel, ported from the HyperBlur plug-in. Its radius reaches 500 ms, and 5 s at every sample rate with ×10. Its latency follows the kernel, from 1 sample to what it needs, where the plug-in is always 4098 samples late. This build has no sidechain yet, so its Signal Kernel model passes the dry signal. |

## Install

In Patchbay Launcher: **Sources**, the **Devices** tab, **+ Add**, type `roguefort-dev/HyperMods` and click **Check**. HyperBlur is then under **Devices**: tick it and click **Download ticked**.

By hand: in Patchbay's window, add this repository's `Bitwig-6.1.7` folder under **Tools > Device Folders**.

The device is for Bitwig Studio 6.1.7 and later. Its output is as late as its kernel needs (69 samples for the default one) and it tells Bitwig whenever that changes.
