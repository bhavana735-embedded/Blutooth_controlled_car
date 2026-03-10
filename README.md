# Blutooth_controlled_car
Built a Bluetooth-controlled robotic car using a microcontroller, motor driver, and Bluetooth module. The car is operated through a smartphone application to control forward, backward, left, and right movements. The project demonstrates wireless communication, embedded programming, and real-time control of motors.
# Aim
To design and implement a robotic car that can be controlled wirelessly using Bluetooth communication between a smartphone and the microcontroller.
# Components Required

Arduino Uno

HC-05 Bluetooth Module

L298N Motor Driver Module

DC Motors (2 or 4)

Robot Car Chassis

Wheels

Jumper Wires

Battery / Power Supply

Smartphone with Bluetooth control app

# Connections
# Bluetooth Module (HC-05)

VCC → 5V (Arduino)

GND → GND

TX → Arduino RX (Pin 0)

RX → Arduino TX (Pin 1)

# Motor Driver (L298N)

Left Motor

IN1 → Pin 8

IN2 → Pin 9

Right Motor

IN3 → Pin 10

IN4 → Pin 11

Enable Pins

ENA → 5V

ENB → 5V

# Power

Motor Driver VCC → Battery

GND → Arduino GND
# Procedure

Assemble the robot car chassis and mount the motors and wheels.

Connect the motor driver module to the Arduino according to the pin configuration.

Connect the Bluetooth module to the Arduino for wireless communication.

Upload the Arduino program to the microcontroller.

Pair the smartphone with the Bluetooth module (HC-05).

Use a Bluetooth control application to send commands such as forward, backward, left, and right.

The Arduino receives the commands and controls the motors accordingly.
