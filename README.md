This is the code to read datas (temperature, humidity and air pressure) from BME680 through ROS2 using Raspberry Pi 4.
I'm using I2C interface. Please check your device address using this command: sudo i2cdetect -y 1. Usually, it is 0x76 or 0x77 (0x77 in my code).

