[![license-badge][]][license] ![version] [![stars][]][stargazers]

# HС-SR04
This is an Arduino library for HC-SR04, HC-SRF05, DYP-ME007, BLJ-ME007Y, SEN136B5B, US-100 (PWM output mode), JSN-SR04T (PWM output mode) ultrasonic ranging sensor

- Operating voltage:    5v
- Operating current:    10..20mA
- Default range:        4cm..250cm
- Measuring angle:      15°
- Operating frequency:  40kHz
- Resolution:           0.3cm
- Maximum polling rate: 20Hz

Features:
- Read distance from 4cm to 250mm**
- Compensate speed of sound according to the ambient temperature
- Pass distance thought median filter
- Set maximum distance to speed up measurement

Tested on:

- Arduino AVR
- Arduino ESP8266
- Arduino STM32

** Sensor returns 38000 if OUT OF RANGE

[license]:       https://choosealicense.com/licenses/gpl-3.0/
[license-badge]: https://img.shields.io/aur/license/yaourt.svg
[version]:       https://img.shields.io/badge/Version-1.2.0-green.svg
[stars]:         https://img.shields.io/github/stars/enjoyneering/HCSR04.svg
[stargazers]:    https://github.com/enjoyneering/HCSR04/stargazers
