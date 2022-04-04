# The Complicated Thermostat
### Make It Overengineered, Stupid

Imagine a place where people with a blurry concept of time go.

They might go there one day but not the next.
Only in the evening or at 9 in the morning.

This place is very cold in the winter, and too hot in the summer.

From this situation comes the need for a remotely controlled thermostat.


## What is needed

- Set a temperature remotely
- Schedule temperatures for the next 24+ hours
- Ask for status information (temperature, humidity, conditioning surce)
- Control one or more conditioning sources
- Use PID logic to change temperature efficiently and precisely


## Technologies

MVP: ESP8266 or ESP32, MicroPython, MQTT and temperature and humidity sensor.
Later on: Telegram bot or interctive Web page and IR transmitter led.

