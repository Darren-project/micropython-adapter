\#docs/micropython-adapter/apis/ultrasonic

# Initalization

````py
import adapters

triggerpin = 5
echopin = 4

ultrasonic = adapters.ultrasonic.Ultrasonic(triggerpin, echopin)
````

# Usage

1. Measure Distance

````py
import adapters

triggerpin = 5
echopin = 4

ultrasonic = adapters.ultrasonic.Ultrasonic(triggerpin, echopin)

print(ultrasonic.measure())
````
