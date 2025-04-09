# DS18B20 using Arduino IDE and SDK

Builds with the v2.3.4 AppImage of the Arduino IDE (`arduino-ide_2.3.4_Linux_64bit.AppImage`) used. The sketch uses Arduino pin 2:

```text
OneWire  ds(2);  // on pin 2 (a 4.7K pullup is necessary)
```

And according to <https://forum.arduino.cc/t/wemos-d1-ds18b20-not-working/680820/4> This maps to `D4` on the ESP itself. And this works.
