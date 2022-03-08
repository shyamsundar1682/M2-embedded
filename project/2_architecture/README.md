# 1.1 block diagram
![Capture](https://github.com/shyamsundar1682/M2-embedded/blob/27a9a8f9380b790325654d1b461ff7f5d4d4aac4/project/2_architecture/block%20digram.PNG)



# 1.2 IR sensor
![Capture](https://github.com/shyamsundar1682/M2-embedded/blob/db507e041925743650e02f77cdfd40e19dc996b9/project/1_requirements/Eye-Blink-Sensor-Working.jpg)

 # Infrared sensors (IR sensor)
  #### Infrared transmitter which acts as the source.
  #### Infrared receiver which acts as the receiver.
  #### Infrared sources include an IR LED and Infrared detectors include photodiodes. 
  #### The energy emitted by the infrared source is reflected by an object and falls back on the infrared detector. 
  #### When the light emitted by the IR LED falls on the receiver, the resistance of the photodiode falls down significantly. 
  #### This photoreceiver is connected with a potentiometer to form a voltage divider circuit, which gives a variable analog output when blinking activity is detected.
  
  # 1.3 RF Transceiver Module
  
  The RF transceiver module is used in the transmission and reception of radio frequency signals.

The RF transmitter module uses Amplitude Shift Keying (ASK) and operates at 433MHz. The transmitter module takes serial data input and transmits that signal through RF. The transmitted signals are then received by the receiver module wirelessly.

Ground: Transmitter ground. Connect to the ground plane.
Data: Serial data input pin.
VCC: Supply voltage; 5V.
ANT: Antenna output pin.

# 1.4 RF Receiver

The RF receiver module receives the data and sends it to the data OUTPUT pin. The output data can be decoded by the Microcontroller for further action.

Ground: Receiver ground. Connect to the ground plane.
Data: Serial data output pin.
VCC: Supply voltage; 5V.
ANT: Antenna output pin.

  # 1.5 12V DC power supply
  
  Its basically takes an input of 14-20V AC or DC and outputs a constant voltage of 12V. 
  
  It can supply a maximum of 1A of current at 12V. 
  
  The board comes with appropriate rectification, filtering circuit, a power indication LED and mounting holes for easy mounting.
