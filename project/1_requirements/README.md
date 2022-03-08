## 1.Arduino based Driver Drowsiness Detection & Alerting System

## 1.1 Description
Road accidents became a matter of concern due to the huge increase in traffic. The primary cause of accidents is due to the drowsiness of drivers in the nighttime. Fatigue and drowsiness are some of the leading causes of major accidents on Highways. The only solution to this problem is detecting the drowsiness and alerting the driver.

## 1.2 Abstract
We know that roads accidents occurs for a variety of reasons.  Some of the leading causes of distracted driving accidents include using a cell phone, over speeding of the vehicle etc etc....
 One of the major reason that while driving vehicle driver getting drowsy to prevent this we build a Driver Drowsiness Detection and Alerting System for Drivers using Arduino Nano, Eye blink Sensor, and RF Transceiver module. The basic purpose of this system is to track the driver’s eye movements using Eye blink Sensor and if the driver is feeling drowsy, then the system will trigger a warning message using a loud buzzer alert.
 
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
| LLR_05 | HLR_03 | It shall trigger a warning message using a loud buzzer aler

## Swort analysis

![Capture](https://github.com/shyamsundar1682/M2-embedded/blob/2aa43332b92a15bbd4c20814fea465757dd9f822/project/1_requirements/Capture.PNG)

![Capture](https://github.com/shyamsundar1682/M2-embedded/blob/db507e041925743650e02f77cdfd40e19dc996b9/project/1_requirements/Eye-Blink-Sensor-Working.jpg)




	
	
	

