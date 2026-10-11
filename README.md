# ohstem

![GitHub License](https://img.shields.io/github/license/marie-curie-stem/ohstem)
![GitHub Release](https://img.shields.io/github/v/release/marie-curie-stem/ohstem)

Student projects with the ohstem teaching kits.

1. Tutorial
2. RGB Module
3. Button RGB
4. LCD Monitor
5. Module Temperature - Humidity DHT20
6. Light Sensor
7. Gas Sensor
8. PIR Sensor
9. Ultrasonic Sensor
10. Moisture Sensor
11. Motor AC
12. Relay

The Project with GANTT chart:

[STEM MARIE CURIE SCRATCH](https://github.com/users/Renartx/projects/1)

## Arduino support

You can program the Yolo UNO directly from their website with your browser, it detects the serial interface. If you want to use Arduino, you need to import the description into the board manager.

> Arduino IDE > Settings > Preferences (Settings) > Additional boards manager URLs: \[  \]

Add

```
https://raw.githubusercontent.com/AITT-VN/ohstem_arduino_board/main/package_xcon_index.json
```

When connecting to your Yolo UNO board with Arduino, you have to confirm to install **"OhStem Boards [v 3.1.3]"** download the OhStem board definition 3.1.3 with ESP32-S3. It will install **platform: 'OhStem:esp32:3.1.3'**.
