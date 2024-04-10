Leverages [JonnyHaystack/joybus-pio](https://github.com/JonnyHaystack/joybus-pio) to let use two DK Bongos layed-out in a diamond as a Dance Pad with your GameCube!

1. Wire up a device according to the schematic in the comments of `main.cpp`. I used a couple of [GameCube Controller Connector w/ Breakout PCB's](https://electron-shepherd.com/collections/all/products/gamecube-connector-w-breakout-pcb) from Electron Shepherd, and half of a [GameCube controller extension cable](https://stoneagegamer.com/controller-extension-cable-for-gamecube-ttx.html).
1. Install [PlatformIO](https://docs.platformio.org/en/latest/). Either the IDE or the CLI version should be fine.
1. Connect a Raspberry Pi Pico to your computer.
1. Put it into boot mode.
1. Upload the firmware with PlatformIO. To do this in the CLI, type `platformio run --target upload`
1. Test with [GC Controller Test](https://www.gc-forever.com/forums/viewtopic.php?t=2305).
