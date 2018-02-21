# Bar Monitor for Rainmeter

A simple system monitoring Rainmeter skin set designed to be compact, informative, and sleek.

This skin set is in its early stages, and is subject to changes and additions as I make them.

## Installation 

This skin requires [CoreTemp](http://www.alcpu.com/CoreTemp/) for the CPU monitor. I suggest setting it 
to start with Windows if you have Rainmeter set to do so.

Then download the files into a folder and place it in your Rainmeter skins directory, 
usually located at `C:\Users\<YOUR USERNAME>\Documents\Rainmeter\Skins`. Then, from the Rainmeter
skins contextual menu, navigate to BarMonitor and click on the skins you'd like to use to activate them.

In the future, I'll include a `.rmskin` version of this skin to simplify installation. 

**Note:** Currently the CPU/RAM portion of the skin is configured for a 6-core CPU. If your CPU has a
different number of cores, you'll have to edit the `NumCores` variable and the number of core `measure`s
and `meter`s. In the future I'll include a script to make this process more convenient.

## Configuring

At the top of each `.ini` file is a `[Variables]` section containing several tweakable parameters. Each one
is briefly described in a comment above it. The only one that must be set correctly is `NumCores`; everything
else can be changed to suit your tastes and the rest of the skin should adapt accordingly.

## Planned Features

- [ ] GPU monitor skin with core frequency, percent usage, and VRAM usage.
- [ ] Storage monitor skin supporting multiple drives, and showing free space and current load for each.
- [ ] Network usage monitor
- [ ] Configuration script to simplify customization for different hardware.
- [ ] Screenshots in this readme.
