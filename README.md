#IMU_9250 IMU_6050 learning code

## Introduction
<!--A brief description of the purpose and functionality of the project.-->
This repo was created for learning purposes regarding how to use an IMU, particularly the MU9250. Several example codes and tutorials are used, while the main purpose of this repo is providing an updated working example in order to provide a smooth introduction to orientation sensing and representation.

## Requirements
<!--A list of all system requirements and required third-party components.-->
In order to successfully run this code, you will need:

* 1 Arduino Uno board (for other boards you will need to check the assigned ports)
* 1 Invensense MU6050 or any breakout board including it.
* 1 USB cable and some wires for connecting the IMU, the Arduino board and the computer.
* Arduino IDE
* Processing IDE

## Installation & Configuration
<!--Step-by-step instructions, with proper punctuation, on how to install and configure the project.-->
* Download and install the Arduino IDE and the Processing IDE.
* Install the MPU6050 library on the Arduino IDE and the Processing IDE.
* For the wirings, follow the **Step 1** from the [tutorial from Arvind Sanjeev at DIY Hacking website](https://webcache.googleusercontent.com/search?q=cache:R-wfCXFXWtsJ:https://diyhacking.com/arduino-mpu-6050-imu-sensor-tutorial/+&cd=1&hl=en&ct=clnk&gl=de&client=firefox-b-ab#attachment_7231).
* Download and install on the Arduino IDE the [MPU6050](https://github.com/jrowberg/i2cdevlib/tree/master/Arduino/MPU6050) and [i2cdevlib](https://github.com/jrowberg/i2cdevlib/tree/master/Arduino/I2Cdev) libraries developed by [Jeff Rowberg](https://github.com/jrowberg).
* When both libraries are installed, open on the Arduino IDE the [MPU6050_DMP6.ino](https://github.com/jrowberg/i2cdevlib/blob/master/Arduino/MPU6050/examples/MPU6050_DMP6/MPU6050_DMP6.ino) example.
* Flash it on your Arduino board and look at the output through the Arduino IDE's Serial Monitor.
* Install the 'Toxi' library for the Processing IDE. For this, download the libraries from [this link](https://bitbucket.org/postspectacular/toxiclibs/downloads/) and add them to the libraries folder from Processing like explained [here in the Processing IDE forum](https://processing.org/discourse/beta/num_1269728211.html#9).
*  Now it is time to modify the files to make them directly work with the 3D representation. Follow the steps from the section **step 3** from [Arduino MPU 6050 by Arvind Sanjeev](https://diyhacking.com/arduino-mpu-6050-imu-sensor-tutorial/#attachment_649) taking the following considerations into account:
	* On Apple computers, you can find the port where your Arduino board is connected by running ` ls /dev/tty.*` on the terminal.

<!--## Build & Deployment-->
<!--Location where the project is deployed, CD & CI cycle.-->

## Documentation
<!--Links to relevant documentation repositories, internal and external.-->
* [Arduino MPU 6050 by Arvind Sanjeev](https://diyhacking.com/arduino-mpu-6050-imu-sensor-tutorial/).
* [Sparkfun's MPU-9250 hookup guide](https://learn.sparkfun.com/tutorials/mpu-9250-hookup-guide#library-and-example-code).
* 

## License
<!--The license under which the software will be released. Open-source projects MUST include the MIT License, and closed-source projects MUST include a proprietary license to be discussed with the Documentation team.-->
These examples and codes were not developed by my person. The libraries and code used here are open sourced and belong to [Kris Winer](https://github.com/kriswiner)(MPU9250BasicAHRS.ino),[Brent Wilkins](https://github.com/BrentWilkins)(MPU9250BasicAHRS.ino) , [Karsten Schmidt](https://github.com/postspectacular/)(Toxi library), [Jeff Rowberg](https://github.com/jrowberg) (i2cdevlib and MPU6050 libraries).

This README.md file written by myself is also Open Source. You may use it, forward it or modify it as you want.

## Contact
Gonzalo Parra-Alvarez. Email me [here.](mailto:gonzalo.pa@protonmail.com)