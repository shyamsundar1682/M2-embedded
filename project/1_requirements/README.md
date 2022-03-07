## 1.Arduino based Driver Drowsiness Detection & Alerting System

## 1.1 Description
Road accidents became a matter of concern due to the huge increase in traffic. The primary cause of accidents is due to the drowsiness of drivers in the nighttime. Fatigue and drowsiness are some of the leading causes of major accidents on Highways. The only solution to this problem is detecting the drowsiness and alerting the driver.

## 1.2 Abstract
 In this project, to build a Driver Drowsiness Detection and Alerting System for Drivers using Arduino Nano, Eye blink Sensor, and RF Transceiver module. The basic purpose of this system is to track the driver’s eye movements using Eye blink Sensor and if the driver is feeling drowsy, then the system will trigger a warning message using a loud buzzer alert.
 Among other causes of road accidents, distracted driving is the most common cause of road accidents around the world, resulting in more crashes every year than speeding, drunk driving, and other major accidents causes. Drivers can become distracted behind the wheel for a variety of reasons. Some of the leading causes of distracted driving accidents include using a cell phone, particularly texting while driving, is the most dangerous form of distracted driving.
 The eye blink sensor is used to detect the eye blinks and using which we can also detect the activities like the Drowsiness of the driver while driving. It works based on the technology of Infrared LED. It contains an Infrared transmitter and Receiver LED which is used to detect the eye blink.
 Infrared transmitter which acts as the source, and infrared receiver which acts as the receiver. Infrared sources include an IR LED and Infrared detectors include photodiodes. The energy emitted by the infrared source is reflected by an object and falls back on the infrared detector. When the light emitted by the IR LED falls on the receiver, the resistance of the photodiode falls down significantly. This photoreceiver is connected with a potentiometer to form a voltage divider circuit, which gives a variable analog output when blinking activity is detected.
 
## 1.3 Identifying features:
i) Arduino Nano.

ii) Eyeblink Sensor.

iii) RF Transceiver Module.

iv) HD12E & HD12D IC.

v) Buzzer.

vi) 9V Battery.

vii) 12V DC power supply.

## 1.4 State of art:
Drowsiness decreases reaction time which is a genuine component of secure driving. 

It likewise lessens readiness, cautiousness, and focus with the goal that the ability to perform consideration based exercises for example driving is hindered. 

The speed at which data is handled is additionally diminished by drowsiness.

## 2 Requirements:

## 2.1 High level requirements:

| HILR | DESCRIPTION |
|------|-------------|
| HLR_01	| This shall monitor the blinking of eyes |
| HLR_02	| This shall Alert the drivers |
| HLR_03	| It shall trigger a warning message using a loud buzzer alert |

## 2.2 Low level requirements:
| LLR |	HLR |	Description  |
|-----|-----|----------------|
| LLR_01 | HLR_01 | This shall detect the drowsiness |
| LLR_02 | HLR_01 | It	alert the driver |
| LLR_03 | HLR_02 | It build a Driver Drowsiness Detection through RF Transceiver module |
| LLR_04 | HLR_02 | It shall track the driver’s eye movements using Eye blink Sensor |
| LLR_05 | HLR_03 | It shall trigger a warning message using a loud buzzer alert |
	


	
	
	

