# UltrasonicAarmSystem
Alarm system with ultrasonic proximity sensors

When the proximity sensor is triggered (when approaching or moving away to a certain distance or when motion is detected), a sound signal or a pre-made recording is output. Each sensor can be configured independently. The recording displayed on the speakers is different, depending on the triggered sensor, or one for all
The sound signal can be turned off either after the obstacle disappears, or will continue until manual shutdown. 

It is possible to install sensors both in parallel with overlapping fields of view (the formation of a certain zone, approaching which will trigger an alarm) or in a chain (an invisible plane, the intersection of which will trigger an alarm).

Audio recording files are stored in mp3 format on a microSD card. 
The system is assembled in a compact case for wall mounting with power connectors (7-12V) and a 3.5 jack for connecting a speaker. Various types of sensors can be connected to the system - infrared photoelectric, ultrasonic, laser. (test sample assembled using ultrasonic sensors).

## Functions
System can be installed in different configuration to use for following reason:
* Alarm system to turn on audio signal (loud siren or unheard from outside warning) 
* Perimeter control system for notification of crossing the control line. Can be used for a sound signal and for counting the number of movements
* Visitors counting system, when after crossing the control line the counter is triggered
* Traffic control, when, thanks to the installation of a pair of sensors in succession, it becomes possible to determine in which direction the intruder was moving
* Automatic system for turning on lighting and other smart home functions (triffered by approaching control line)
 
## Installation
System can be installed in different configuration:
1 Parallel installation of sensors. 
 	Allows to accurately determine the approach distance for triggering. Due to the relatively narrow field of view, each sensor covers a front up to 1 m wide and up to 4 m deep

1 Sequential installation of sensors (on poles, trees or other objects). 
 
Allows you to form a chain that makes up an extended control line. Since all sensors are configured to operate at any distance, the system is triggered only discretely (the approach distance cannot be adjusted) The length of the control line depends on the number of sensors in the chain (up to 4m per sensor)

1 Installation of sensors in the gate opening. 
 	Allows you to control the intersection of an opening at any height (birds, drones, etc.)
Each of the sensors allows you to cover 3-4m2. Due to the geometry of the field of view, it is advisable to install sensors with overlap.

## System parameters:

* Main controller		– Arduino Uno 
* Processor 			– 16 MGh, ATmega328P
* Controller memory		– 32 KB Flash + 2 kB SRAM + 1kB EEPROM
* Audio decoder			–VS1053B
* Supporting formats		– MP3/AAC/WMA/MIDI
* audio output jack		– 3.5mm
* Proximity sensors 		– HC-SR04 
* Sensor type			– ultrasonic sensor
* Sensor range 			– 2..400cm
* Angle of view			– 15°
* Power supply 			– 9 V, 500mA
* Dimensions
    - 60x80x20 (main case)
    - 37x20x15 mm (each sensor) 
    - 2m (sensor cable length)
* Weight
    - 100 g (main case)
    - 230 g (whole package with controller box, power supply, 3 sensors and wiring)


## Components
* Controller Arduino UNO 
* SparkFun MP3 Player Shield
* MicroSD card 2Gb
* Ultrasonic Proximity sensors  HC-SR04 – 3 pcs
* Power supply 220V/120V - > 9V 500mA


## Wiring diagram
 

## Further development of the system
* Connection different types of sensors (infrared, laser, capacitive)
* Connection to Smart home network
* Increase quantity of sensors
* Adding subgroups of sensors with different triggering parameters and signal type
* Remote control of system:
    - Remote control (Bluetooth, 2.4GGh etc.)
    - Web interface
    - Control via mobile network (SMS-informing and control commands)

## Photos


 
 
 
