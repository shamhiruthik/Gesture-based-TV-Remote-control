# Gesture-based-TV-Remote-control

It is a project on GESTURE BASED TV REMOTE CONTROL using Ultrasonic sensor and IR transmitter interfacing with Arduino UNO. For television we are using HEX code but here we are using RGB LED where the all commands will be shown a serial monitor and with different colours on RGB. We can interface with our TV Where swiping over within the specified range in code shows different colours on RGB and different operations if you are using the TV.

## Working

-	`POWER:` Swiping over the sensor within 3 inches will cause the LED to flash purple. This is the confirmation that a 'turn on / off' signal is ready to be sent. To prevent it accidentally turning the TV off I have made the sketch wait for a second swipe within 5 seconds of the first to confirm. At this point, the signal is sent to the TV to turn on or off.
- `CHANNEL:` Swiping within 10 inches of the sensor (but not within 3) will cause the channel to change down. Swiping between 10 and 20 inches will cause the channel to change up.
- `VOLUME:` Holding your hand within 10 inches of the sensor (but not within 3) will cause the volume to change down. Holding between 10 and 20 inches will cause the volume to change up. The volume will continue to change (up or down) until your hand is removed.

## Hardware Required:

- Arduino uno with USB cable – 1
-	Ultrasonic sensor HC SR04 – 1
-	Breadboard 400 point – 1
-	RGB Led – 1
-	IR led – 1
-	Single stand wire 2m - 1
-	Resistor 220 ohm – 3
-	Jumper wires male to female– 40 Pieces 
-	Jumper wires male to male– 40 Pieces 
 
## Software Required:                                                                                               

-	Arduino IDE 1.8.5
