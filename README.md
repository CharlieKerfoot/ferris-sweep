## Ferris Sweep

The original [Ferris Sweep](https://github.com/davidphilipbarr/Sweep) is a 34-key ergonomic split keyboard, made by [David Barr](https://github.com/davidphilipbarr). 

I originally gained interest as I've heard many say that is make typing more fun and it works very well in tandem with mouse-less software like Vim. The version I have made, which includes jagged top rather than the traditional curve, is heavily inspired by [Ben Vallack](https://www.youtube.com/watch?v=JqpBKuEVinw), but uses the original Sweep format instead of the compact that Ben used. I also choose to make it wireless using [nice!nano](https://nicekeyboards.com/nice-nano/) microcontrollers, and fully hot-swappable using Mill-Max hotswap sockets.

## Part List
These were the exact parts that I used. You can customize most of it like the switches or the size of the sockets.

1 Ferris Sweep PCB (see gerberfile)
2 nice!nanos
2 3.7V lithium batteries
68 0305 Mill-Max hotswap sockets
34 Kailh Choc v1 Brown switches
34 Kailh Low Profile PBT Blank keycaps
2 MSK-12C02 on/off switches
4+ Rubber Feet
1 USB C cable

## Build Guide

[nice!nano build guide](https://www.youtube.com/watch?v=zoCKINGh2DQ)
[Mill Max sockets](https://www.youtube.com/watch?v=wmkTVsZ97Vk)
[Ferris Sweep build guide](https://www.youtube.com/watch?v=fBPu7AyDtkM)

## Firmware

Since my Ferris Sweep is wireless, I use [ZMK](https://zmk.dev/). Here is my [config](https://github.com/CharlieKerfoot/zmk-config)
