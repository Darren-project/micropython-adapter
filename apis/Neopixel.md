\#docs/micropython-adapter/apis/neopixel

# Initalization

````py
import adapters

NUMBER_PIXELS = 2
STATE_MACHINE = 0
LED_PIN = 18

# The Neopixels on the Maker Pi RP2040 are the GRB variety, not RGB
strip = adapters.neopixel.Neopixel(NUMBER_PIXELS, STATE_MACHINE, LED_PIN, "GRB")
````
