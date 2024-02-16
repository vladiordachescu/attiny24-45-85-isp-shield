# ATtiny25/45/85-ISP-shield

The shield uses an Arduino Uno as an In-System-Programmer (ISP).<br />
The ISP code can be found in the Arduino IDE at **File > Examples > ArduinoISP**.<br /><br />
Note that the shield uses the old style wiring, so the ISP code must be modified:

![image](https://github.com/vladiordachescu/attiny25-45-85-isp-shield/assets/73362552/782d1419-a183-49df-bc8b-09dc2e4e3951)

## The printed shield
![sheild](https://github.com/vladiordachescu/attiny25-45-85-isp-shield/assets/73362552/e4e0737e-0ea5-419b-ab24-005f1c8064f7)
![shield-on](https://github.com/vladiordachescu/attiny25-45-85-isp-shield/assets/73362552/7ae46bbf-8211-4899-a41a-81bef70b6808)

The shield pins must match the header pins of the Arduino Uno.
The 10uF capacitor on the shield prevents the Arduino Uno's microcontroller from resetting during the programming of the ATtiny microcontroller.
