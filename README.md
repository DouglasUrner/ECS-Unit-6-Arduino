# ECS-Unit-6-Arduino

An alternative to the ECS Robotics Unit (Unit 6) using an Arduino and the Zumo Bot robot chasis and control board.

## Getting Started

### What to order

### Robot assembly

Notes on things that might not be obvious…

1. Decide how you want to set the buzzer jumper on the Zumo. Out of the box the jumper isn't connected and the buzzer (sounds) don't work. To enable sounds install jumper between the pins labeled 328P (towards the back of the chasis).

### Software

Initially I'm using the stock Arduino IDE (1.6.3 at this writing). It should be possible to also use Scratch, but that looks like it will take some work.

1. Download the [Arduino IDE](http://arduino.cc/en/Main/Software). Depending on your host platform, you may also need to install or update Java.
2. Install the Zumo Bot extensions

I'm going to work on setting it up so that you can also install the "whole ball of wax" by cloning this repository.

## Day by Day

### Day 1: Introduction - What is a robot?

Attributes of a robot:

* Body

  Physical manifestation and a means of interacting with the world.

* Control
 * Input

   Information and materials from the world.

 * Program

   The instructions that implement the robot's behavior.

 * Output

* Behavior - the way the robot responds to inputs and produces outputs. The behavior is responds to the inputs (a robot finds solutions to problems).

#### Shoe Tying

Wood with holes

Lace in holes

Clips for robot hands

Gloves

### Day 2: Behavior Control Algorithms



#### Resources:

* [Official Arduino Introduction](http://www.arduino.cc/en/Guide/Introduction)

* [Zumo Manual (HTML)](https://www.pololu.com/docs/0j57)

* [Zumo Manual (PDF)](https://www.pololu.com/docs/pdf/0j57/zumo_shield_for_arduino.pdf)

### Day 3: Arduino Introduction

Norms for handling robots.

Assign groups of four students.

Roles in group:
1. Facilitator
2. Hardware
3. Documentation
4. Programmer dejour

Observe board, connect back to Unit 1. A large clear image of the component side of the board is [here](http://www.arduino.cc/en/uploads/Main/ArduinoUno_R3_Front.jpg).

Start block diagram

Components to find:
* Atmel ATMega328P microcontroller (integrated chip with CPU, RAM, flash memory, it is the largest chip on the board)
* Atmel ATMega16U2 microcontroller (the surface mount chip with lots of pins near the USB connector, it is a general purpose microcontroller that is used to handle the USB communication between the host computer, the PC used to write the programs for the Arduino, and the Arduino)
* USB connector
* Reset buttom
* Analog pins
* Digital pins
* PWM (pulse width modulated) pins
* Power connector
* Pin 13 LED
* TX/RX LEDs
* Power LED

### Day 4: Arduino IDE: Blink & Beep

#### Arduino program model:

##### Using Scratch:

[Mblock](http://mblock.cc)

[S4A: Scratch for Arduino](http://s4a.cat)

On a Mac (at least with OS X Yosemite, 10.9, and Mavericks, 10.10) you will need to set your Security & Privacy preferences in System Preferences to install the application (drag it into the Applications folder)

##### Using Arduino IDE:

Code is written using C/C++ syntax. The Arduino IDE handles some of the details of how C/C++ code is structured. The IDE provides a number of canned examples.

The Arduino programming model is based around two functions.

```
setup() // Code that is executed once to get ready.
```
and
```
loop() // Code that runs over and over doing the work of the machine.
```

Scratch blocks and C code are very similar.

#### Resources:

##### Scratch

##### Arduino IDE

* [Arduino IDE Downloads](http://www.arduino.cc/en/main/software) - the Arduino IDE is written in Java so you may also need to download and install Java.

* [Zumo extensions for the Aruduino IDE](https://github.com/pololu/zumo-shield) - these are the components that need to be added to the stock Arduino IDE to support the Zumo.

##### Command Line Tools

### Days 5 & 6: Walk Like a Robot

### Day 7:

### Day 8:

What?

### Day 14:

### Day 15:

### Day 16:

### Days 17 & 18: Line Following Challenge
