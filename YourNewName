# SPDX-FileCopyrightText: 2021 Kattni Rembor for Adafruit Industries
#
# SPDX-License-Identifier: MIT

import time
import board
import neopixel

# Calls the CircuitPython neopixel library, specifies the default board 
# pins for the NeoPixels, and the number of NeoPixels to access. Returns a 
# list 'pixels' of indexable NeoPixels
pixels = neopixel.NeoPixel(board.NEOPIXEL, 5, brightness=0.2)

while True:
    # Flash pattern for the first three NeoPixels
    pixels[0:3] = [(255, 0, 0), (0, 0, 0), (255, 0, 0)]
    time.sleep(0.5)
    pixels.fill((0, 0, 0))
    time.sleep(0.5)
