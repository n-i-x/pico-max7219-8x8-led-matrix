# WORK IN PROGRESS
This is a work in progress and is subject to completely change.


# raspberry pi pico pio-accelerated max7219 8x8 LED matrix driver
This should provide a basic ability to update a chain of max7219 8x8 LED matrices or 7-segment displays at extremely high speed with very little CPU utilization, thanks to the power of the pio!

# TODO

* cleanup, turn into library
* add memory map for pixel grid, and feature to automatically DMA the mapped memory to the PIO on a timer
* add initialization helpers and helpers for the max7219 registers
* add helpers for 7-segment decoding (for now, just check the max7219 datasheet)