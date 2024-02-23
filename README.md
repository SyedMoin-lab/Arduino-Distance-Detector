# Ultrasonic Sensor Distance Detection with LCD Display

This project demonstrates how to use an ultrasonic sensor to measure distance from objects and display the result on a 16x2 LCD screen using an Arduino board.

![Arduino-Distance-measurement-using-ultrasonic-Sensor](https://github.com/SyedMoin-lab/Arduino-Distance-Detector/assets/63508680/96c60bab-12cd-4770-8465-a292be56f34a)


## Overview

Ultrasonic sensors are commonly used for distance measurement in various applications. In this project, we utilize an ultrasonic sensor to measure the distance between the sensor and an object in front of it. The measured distance is then displayed on a 16x2 LCD screen in real time.

## Components Required

- Arduino Uno (or any compatible board)
- HC-SR04 Ultrasonic Sensor
- 16x2 LCD Display
- Potentiometer (for adjusting LCD contrast)
- Breadboard
- Jumper wires

## Installation and Setup

1. Connect the components as per the circuit diagram provided (TODO: Add circuit diagram).
2. Upload the Arduino sketch provided (`ultrasonic_lcd_display.ino`) to your Arduino board using the Arduino IDE.
3. Adjust the contrast of the LCD using the potentiometer.
4. Power on the Arduino board.
5. The LCD will display the distance measured by the ultrasonic sensor in centimeters.

## Usage

- Place objects in front of the ultrasonic sensor at varying distances to observe real-time distance measurement on the LCD display.
- The LCD will continuously update the distance measurement as objects move closer or farther away from the sensor.

## Contributing

Contributions are welcome! If you'd like to enhance this project or fix any issues, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Arduino](https://www.arduino.cc/) for providing the Arduino platform and libraries.
- [Ultrasonic Sensor Library](https://github.com/JRodrigoTech/Ultrasonic-HC-SR04) by J.Rodrigo.
- [LiquidCrystal Library](https://www.arduino.cc/en/Reference/LiquidCrystal) for interfacing with the LCD display.

## Author

[Your Name] - [Your Website or GitHub Profile]

