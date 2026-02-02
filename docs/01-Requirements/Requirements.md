---
title: Human Machine Interface Requirements
---

## Human Machine Interface Requirements
The following sections document the requirements that this Human Machine Interface module needs to fulfill to meet device requirements set by team 303 for our ground search and rescue drone and the mandated Human Machine Interface requirements for this class. 

The Human Machine Interface is a required user interface on the bot that interacts with the whole subsystem using pushbuttons and an OLED screen. 

| Requirements Description | Measure of Threshold | Target Measure | Stretch Requirement |
|---|---|---|---|
| Surface mounted, 3.3V switching power regulator | 3.2V | 3.3V | N |
| Surface mounted microcontroller | 1 PIC or ESP | 8-bit PIC | N |
| Wireless Communication | Bidirectional communication between vehicle and control | Bidirectional communication between vehicle and control or status feed without wires | Y |
| Display live video | Sends out 30 FPS per second | Live video with less than 3 seconds of delay | Y |
| Human Design Interface; Respond manually with buttons | Small OLED screen with pushbuttons that permits a user to view all sensor data in text; directly control the actuator; modify setpoints on all the system boards; toggle GPIO debug pins on ALL subsystems. | All the content in MoT and ability to tune sensors and actuators with controls on exterior of device. | N |
| Daisy chain UART | Daisy chain UART connection between all subsystems | Separate UART loops for high speed communication through certain subsystems | N |
| Device must be able to communicate to survivors using a speaker | Is able to playback audio sent from an HMI device and listen to its environment. | Is able to playback audio sent from an HMI device and listen to its environment in a hearable range of 90 db, 2 - 5 kHz. | Y |
| Locomotion Control | Directly controls locomotion for moving forward, reverse, and turning. | Directly controls each wheel individually | N |
| Wireless Control | Displays status and controls connection status for the wireless system. | Displays bit rate and packets of wireless data transmission. Manual control over which wifi channel to use. | N |
| Arm Control | User controls for general arm movement. | Precise user controls for exact degree movement for arm motors. | N |
| Camera/distance sensor Control | Displays camera and distance sensor status and readings. Ability to turn on and off camera and distance sensors. | Ability to fine tune camera and distance sensor. | N |
| Microphone/Speaker Control | Displays graphical output from microphone and input to speaker. Ability to turn microphone and speaker on and off. | Ability to change microphone sensitivity and speaker volume. | N |

