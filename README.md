# Android Application Controlled Grip Car Robot with Arduino-based Bluetooth Communication

Control your car robot using an Android app with Bluetooth communication! This Arduino-based project enables precise control of the car’s movement and grip functionalities directly from your smartphone, offering an intuitive and interactive way to navigate and manage your robot car.

## Features

- **Apk Joystick for only Android**
- **Forward Movement**: Moves the car robot forward.
- **Backward Movement**: Moves the car robot backward.
- **Left Turn**: Turns the car robot left.
- **Right Turn**: Turns the car robot right.
- **Grip Control**: Adjusts the grip using servos (open and close).
- **Lift Control**: Controls the lifting mechanism of the robot using servos.

## Components

- Apk for only Android.
- Arduino board (e.g., Arduino Uno)
- 2 Servo motors
- 4 DC motors with motor driver
- Bluetooth module (e.g., HC-05 or HC-06)
- Power supply

## Circuit Diagram

- **Motor Pins**: Connect to the motor driver for controlling movement.
- **Servo Pins**: Connect to pins 7 and 8 for grip and lift control.
- **Bluetooth Module**: Connect to the RX and TX pins of Arduino for communication.

## Code Description

- **`maju()`**: Moves the robot forward.
- **`mundur()`**: Moves the robot backward.
- **`kanan()`**: Turns the robot right.
- **`kiri()`**: Turns the robot left.
- **`gripin()`**: Closes the grip.
- **`gripout()`**: Opens the grip.
- **`gripup()`**: Lifts the grip.
- **`gripdown()`**: Lowers the grip.
- **`berhenti()`**: Stops all movements.

## Usage

1. **Upload the Code**: Upload the Arduino sketch to your Arduino board.
2. **Connect Bluetooth**: Pair your Bluetooth module with your Android device.
3. **Control the Robot**: Use an Android app to send commands to the robot via Bluetooth.

## Commands

- **'1'**: Move forward
- **'2'**: Turn left
- **'3'**: Move backward
- **'4'**: Turn right
- **'5'**: Lift grip
- **'6'**: Close grip
- **'7'**: Lower grip
- **'8'**: Open grip

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Arduino community for providing resources and libraries.
- Contributors and developers of Bluetooth communication libraries.
