# EIS_core
Intelligent Switch
I'm planning to do home automation, but "smart" switches on market don't meet my requirements, software isn't open 
or just cost a fortune. So, I've decided to design Intelligent Switch packed up with sensors which don't cost 
fortune and is fully open source for anyone.

What can I do with Intelligent Switch?
- Gesture control, light, garage doors, house alarm, multi zone thermostat, sound system, virtually anything, you name it! 
- OLED display for user feedback
- Temperature and humidity readings per switch
- Microwave presence detector, doppler radar (aka PIR) 
- Ambient light measurement

All programming will be done in Arduino IDE. With MQTT funcitionality for easy integration with OpenHAB, HomeAssistant and Domoticz.

Software:
- OTA (TODO)
- WiFi Manager (TODO)
- MQTT (TODO)
- RTC/NTP (TODO)

Eagle diagrams:
- 220V/110V to 3.3V (In progress)
- Sensor board (In progress)

Enclosure
- Visual design (TODO)
- CAD design (TODO)

Hardware list:
- OLED 0.96
- Gesture sensor APDS9960 (issue with blocking, consider another microprocessor with i2c communication just to read gestures)
- Temperature sensor
- Presence microwave sensor

Consideration:
Funding for prototyping, CE conformity, testing and manufacturing.
