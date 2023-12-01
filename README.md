# Arduino Gesture-Controlled Glove
## Overview
This Arduino project implements a gesture-controlled Glove using the MPU6050 accelerometer and flex resistors. The system interprets hand movements and gestures to trigger specific responses, creating an interactive and hands-free device.

## Components
- MPU6050 accelerometer
- Flex resistors (adc1 to adc4)
- LED (connected to pin 13)

## Features
1. **Gesture Recognition:** The MPU6050 captures motion data, allowing the system to respond to specific gestures.
2. **Flex Sensor Input:** Flex resistors detect hand flexion, providing an additional layer of control.
3. **Voice Feedback:** Serial communication provides voice-like responses for recognized gestures.
4. **Interactive Responses:** Different gestures trigger varied responses, such as "STOP," "WASHROOM," "MEDICINE," "FOOD," etc.

## Usage
1. When flex1 is less than 200, the system responds to gestures based on MPU6050 readings.
2. If flex2 is less than 30, the system enters a conversational mode, responding to specific queries.
3. The LED on pin 13 provides visual feedback when the system is active.

## How to Use
1. Upload the provided code to an Arduino board.
2. Connect the MPU6050 and flex resistors according to the specified pinouts.
3. Power on the system and observe the LED for activation.
4. Perform gestures or ask questions, and the system will respond accordingly.

## Configuration
- Adjust gesture thresholds and responses in the code to customize the interaction.
- Ensure proper wiring and calibration for accurate gesture recognition.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Thanks to the [MPU6050 library](https://github.com/ElectronicCats/mpu6050) for providing essential functions for working with the accelerometer.

Feel free to contribute and improve upon this project! If you encounter issues or have suggestions, please open an issue in the repository.
