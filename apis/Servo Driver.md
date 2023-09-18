\#docs/micropython-adapter/apis/servo-driver

# Initalization

````py
import adapters

servo = adapters.servo_driver.ServoDriver(3)
````

# Usage

1. Turn the servo

````py
import adapters

servo = adapters.servo_driver.ServoDriver(3)

# Only 0 to 90 degree
servo.move(10)
````
