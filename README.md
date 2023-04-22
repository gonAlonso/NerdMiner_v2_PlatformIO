# NerdSoloMiner on PlatformIO
Based on the project [NerdSoloMiner v2](https://github.com/BitMaker-hub/NerdMiner_v2), wich itself is based on project [HAN](https://github.com/valerio-vaccaro/HAN)

## Requirements
- TTGO T-Display S3

## Description
Ported this example to be compiled and uploaded using [platformio](https://platformio.org/) on [VSCode](https://code.visualstudio.com/)
This allows the toolkit to be held on a Docker container, solving dependencies inside it.

I'm using the [Lilygo T-Display-S3](https://github.com/Xinyuan-LilyGO/T-Display-S3) as develop board. Purchase it Online

* ESP32-S3R8 microcontroller
  * 2-Core 240MHz
  * 84 KB ROM
  * 512 KB SRAM
  * Bluetooth v4 LE
  * Wifi-N 2.4GHz
* 170*620 px LCD display
* 2 buttons
* RST buton
* USB-C port

## How-to
To run it, just:

 * Install VSCode
 * Install **Dev Containers** Extension on VSCode
 * Clone this repo
 * Open VSCode and open the repo folder
 * VSCode automatically detects the Docker config, asking you to start the container. Confirm it.
 * VSCode will start the container, install the configured plugins and run scripts associated.

## About the miner
The underlying miner is just an example test case to probe integrated Dockerization for platformio.
For detailed instructions on how to use the miner, just follow  [BitMaker's repo instructions'](https://github.com/BitMaker-hub/NerdMiner_v2)