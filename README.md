# Building a Bluetooth Controlled Car (Version 1)

The reason for creating this repository is for my Computer Science 207 project on how to build a Bluetooth controlled car using an Arduino and your mobile device. This is created from an example from the Arduino Project Hub that was done by Saman Fernando as well as Janak13. The only twist to the project is that the car senses when it is about to hit something and stops. 
The car will be controlled by your mobile device in this case I used an Android phone to control the car, because the app was not available on Apple. This was then connected to an Arduino UNO as well as a Bluetooth (HC06) and a Motor Driver (L298N), as well as an Ultra Sonic Distance Sensor (HC-SR04).
This project is for my class as mentioned and I thought it would be an easy project to try and to challenge myself a little as I am new to coding and building and using an Arduino. I thought it would be a fun project that my friend’s son could use in the future. However, because of the Coronavirus I had my friend drive the car instead because I could not go over to my other friend’s house.

## Respository Contents

- hardware - All the files for how the project was designed
- build - Files that are compiled and ready to run/upload
- img - Images used in the README.md file
- LICENSE - The license file
- README.md - Currentl file being read
- src - Software used to control the car

## Requirements and Materials
This is all the materials used to complete the build:

- Cardboard
- 4 x motorized toy car wheels
- 1 x on and off switch
- 2 x lithium battery holder
- Jumper wires (generic)
- 2 x Lithium batteries (rechargeable)
- 1 x L298N Motor Driver
- 1 x Arduino UNO
- 1 x HC-06 Bluetooth Module
- 1 x HC-SR04 Ultra-Sonic Sensor 
- 1 x 2.2K Resistor 
- 1 x 1K Resistor 

Lastly you will need an Android Phone which is able to download the app you need to operate the car. The app is called "Arduino Car",
that is the only additional thing you will need.

## Build Instructions
First you want to gather all your material so that they are easily accessible. You want to cut your cardboard into a big enough shape for a car but so that everything will fit on it nicely.
Next you want to attach the Arduino UNO, Motor Driver and Lithium Battery holder onto the cardboard. After that you will want to attach the wheels as well. You can use hot glue which is what I used. You will also want to make a hole and pull the wires from the wheels to the top of the carboard to connect it easier to the Arduino.
Next you will want to connect the wires to the battery to see which way to connect the wires to the motor so that they spin the correct way. The green wires are connected to ground and the blue wires are connected to the volt in. You will want to connect the wires for the right side’s tires together. (green and green and blue and blue together) And then connected a third wire onto the ends of both sides of the tires which will connect to the Arduino. 
After connected the tires to the motor attach power again to make sure the wheels are still going in the correct direction. Next you want to connect the pins to the Arduino. Once that is connected you will want to connect the Bluetooth next and the car is basically almost done. 
You can put the batteries into the holder next and then add the switch to the side of the battery pack. You want to connect the switch onto the positive side of the battery.
Next you will need to add on the sensor. I decided to put the sensor on extra cardboard instead of attaching it directly so that if I need to remove it then it will be easier to remove. You can then wire up the sensor which goes to the ground pin on the Arduino and to echo pin will be connected to pin 11 on the Arduino and the trigger pin is connected to pin 10 on the Arduino and the VCC pin is connected to the 5V pin on the Arduino. 
The only last step is connecting the Bluetooth onto the cardboard and permanently attaching it and then wiring it up to the Arduino. 
After this is all done the car is done being built and all that is left to do is upload the code to the Arduino. If you can’t see from the pictures which pins things are connected to it is in the Code as well.

## Firmware Installation
The code to run on your Arduino is included below.  You should be able to just connect your Arduino to your computer and then hit upload and it should run without any problems.
The only other thing you need to install is the Arduino Car app from the Appstore there should not be any problems with that either if your phone can access the Appstore on Android.

##Usage
Operating the car is simple. First you want to upload to program to you Arduino once it is uploaded unplug the USB from the Arduino. Next you want to turn on the car using the switch. Once you have the car turned you want to open the app on your phone and connect the phone to the Bluetooth. Once this is done the LED on the Bluetooth will stop blinking. You can then begin using the car. 
The car will move forward, turn left and right, and back up if it does not sense an object in front of it. Once the car senses an object in its path it will stop. It will not go forward any more it will only back up and turn right and left. 
That is all you need to do, and you can enjoy using the car.

## Team
There was no team for this project as I did it myself. With just instructional help to problem solve from Wisdom Eji when I couldn’t figure something out because I am extremely new at coding. He is also seen in the video operating the car as I had to film. 

## Credits
This project idea was borrowed from Saman Fernando as well as Janak13 which can be found on the Arduino Project Hub. The links are included below.

https://create.arduino.cc/projecthub/samanfern/bluetooth-controlled-car-d5d9ca
https://create.arduino.cc/projecthub/JANAK13/bluetooth-controlled-car-2c60e9?ref=search&ref_id=Bluetooth%20Controlled%20Car%20%C2%A9%20GPL3+&offset=2



