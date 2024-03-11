# Car-parking-sensor
A simple ultrasonic range finder using 8051 microcontroller to measure distances up to 2.5 meters at an accuracy of 1 centimetre. AT89c51 microcontroller and the ultrasonic transducer module HC-SR04 forms the basis of this circuit.
A sensor is mounted at the back of the car. It detects the distance by sending electromagnetic pulses through a transmitter, reflected by an obstacle. The sensor is connected to the HC-SR04 module. This module works on a 5V DC supply
and the standby current is less than 2mA. It transmits an ultrasonic signal, picks up its echo, measures the time elapsed between the two events and outputs a waveform whose high time is modulated by the measured time which is proportional to the distance.
The microcontroller accepts this signal, performs necessary processing and displays the corresponding distance on the 16x2 LCD. If this distance is less than 20 centimetre, a buzzer is sound.
