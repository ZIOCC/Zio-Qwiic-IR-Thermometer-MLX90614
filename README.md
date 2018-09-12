# Zio-Qwiic-IR-Thermometer-MLX90614

Description

The latest incorporation to our Qwiic family is this high precision temperature module!  It has a very cool feature on sensing temperatures remotely thanks to the infrared light emitted. Most of the object temperature sensors need to be in contact to the object to take a measurement, but the ZIO IR Thermometer determines the light rebounding off objects, in this way the temperature can be sensed even if the object is located in a certain distance. To get a temperature measurement just point the sensor facing the object to evaluate and it will gather the data by absorbing the IR waves diffused.

The board incorporates an MLX90614 sensor, able to measure a wider range of temperatures than other temperature sensors - as it doesn’t need to make contact to the object’s surface. It can be used for many applications, it produces two temperature measurements. One for measuring the ambient temperature and another one to measure ambient temperature.  It measures temperature between -70 and 380°C (or -94 to 719.96 °F) for objects and -40 to 125 °C for ambient temperature.

It has a wide field-of-view angle: 90° - for every cm away from the object, the sensing area increases 2cm.

The sensor uses a 2-wire SMBus interface, with almost the same features as I2C. Actually, the MLX90614 has an I2C address (0x5A) which can be reconfigured. This is an awesome factor if you want to incorporate multiple MLX90614 at the same I2C bus to operate separately.

The multifunctional temperature sensor can also be read via PWM interface through the SDA (no need to use SCL, just use 3 wires for PWM interface). Getting data through PWM can be tricky on some occasions, but on the positive side, it is very powerful. We have also incorporated the sensor pinout at the board, by soldering the pin header provided the PWM interface can be easily used.



Specifications:

    Factory calibrated in wide temperature range:
    -40 to 125  ̊C for sensor temperature and
    -70 to 380  ̊C for object temperature.
    Resolution: 0.02°C
    Single and dual zone versions
    Current Consumption: 25mA
    Dimensions: 16.4 x 26.8mm
    Weight: 2.3g



Links:

    MLX90614 Datasheet: https://www.sparkfun.com/datasheets/Sensors/Temperature/MLX90614_rev001.pdf
    Library link: https://github.com/adafruit/Adafruit-MLX90614-Library
