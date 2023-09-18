\#docs/micropython-adapter/apis/motor-driver

# Initalization

````py
import adapters

motor = adapters.motor_driver.MotorDriver(8,9,10,11)
````

# Usage

1. Move

````py
import adapters

motor = adapters.motor_driver.MotorDriver(8,9,10,11)

# Follow this format (m1a, m1b, m2a, m2b)
# Max value is 65535
motor.control(0,0,0,0)
````
