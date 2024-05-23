# ESPHome-SML-OBIS-Reader
ESPHome configuration example to read Power Meter via IR TTL (Volkszähler)

I'm using an Wemos D1 Mini and a IR Transmitter, 1k Ohm Transistor and some wires. 
![IR Wemos Layout01_Steckplatine_v2](https://github.com/thealkly/ESPHome-SML-IR-LED/assets/106326904/2ab79337-e14b-4363-851a-44883b884dd9)

This configuration works for me with my ED100L Smart Meter from EMH.

If needed change your obis_code accordingly to your Power Meters provided values.
To see which obis_code's are sent from your power meter, you can simply set the log level for sml to DEBUG.


# Device view in Home Assistant
![Screenshot](docs/SmartMeterOBIS.png)
# finished 3D Print with ESP8266 
see https://alkly.de/smart-meter-auslesen-mit-tasmota-esphome/
![Smart Meter ESP IR Reader SML (1 von 14)](https://github.com/thealkly/ESPHome-SML-IR-LED/assets/106326904/06cf5cab-7881-4151-809d-4e024cc1a260)
