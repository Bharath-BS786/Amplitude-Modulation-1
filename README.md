<img width="723" height="935" alt="image" src="https://github.com/user-attachments/assets/2f2a4c35-5a95-4cc6-a8f3-4db4650b4103" /># Amplitude-Modulation

EXP NO: 1	GENERATION AND DETECTION OF AM

AIM:

To generate and detect the amplitude modulation and demodulation u s i n g S C I L A B and to calculate modulation index of AM.

EQUIPMENTS REQUIRED

•	Computer with i3 Processor

•	SCI LAB

THEORY:

Modulation can be defined as the process by which the characteristics of carrier wave are varied in accordance with the modulating wave (signal). Modulation is performed in a transmitter by a circuit called a modulator.
Need for modulation is as follows:
•	Avoid mixing of signals
•	Reduction in antenna height
•	long distance communication
•	Multiplexing
•	Improve the quality of reception
•	Ease of radiation.
Amplitude Modulation is the process of changing the amplitude of a relatively high frequency carrier signal in proportion with the instantaneous value of the modulating signal. The output waveform contains all the frequencies that make up the AM signal and is used to transport the information through the system. Therefore the shape of the modulated wave is called the AM envelope. With no modulating signal the output waveform is simply the carrier signal. Coefficient of modulation is a term used to describe the amount of amplitude change present in an AM waveform. There are three degrees of modulation available based on value of modulation index.
1)	Under modulation :	m<1, Em < Ec
2)	Critical modulation: m-1, Em = Ec
3)	Over modulation:	m>1, Em > Ec



Note: Keep all the switch faults in off position

Algorithm
1.	Define Parameters
First, define the parameters for your signals:
•	Carrier frequency (fc)
•	Modulating signal frequency (fm)
•	Sampling frequency (Fs)
•	Duration of the signal (T)


2.	Create a time vector based on the sampling frequency and duration.
 
3.	Create Modulating Signal
Define the modulating signal (message signal).

4.	Create Carrier Signal
Define the carrier signal.


5.	Perform Amplitude Modulation
Multiply the carrier signal by the modulating signal plus 1 (to ensure the modulation depth).


6.	Plot the Signals
Visualize the modulating, carrier, and modulated signals.


7.	Demodulate the AM Signal
To demodulate, you can use envelope detection. One way is to rectify the signal and then apply a low-pass filter.

8.	Plot the Demodulated Signal
Visualize the demodulated signal.


9.	Compare Signals
Compare the original modulating signal with the demodulated signal. PROCEDURE
•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Program
<img width="723" height="935" alt="Screenshot 2025-10-31 094327" src="https://github.com/user-attachments/assets/08eb9c28-d83a-4931-ae15-6b2976d72c3a" />




Output Waveform

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/ca3a8aa2-8f20-44ef-a7ff-065d382e4160" />




TABULATION:

![ac exp 1](https://github.com/user-attachments/assets/23595c7c-31c6-45b2-92ed-8e973c9703a4)


Calculation
1.	ma (Theory) = am/ac =

2.	ma(Practical) = (Emax-Emin)/(Emax+Emin) =

![ac exp 1 2](https://github.com/user-attachments/assets/c7419537-a1f6-4ee6-bf44-d64f3b6209e9)
![ac exp 1 1](https://github.com/user-attachments/assets/52e2fc69-adf9-4b6e-92a3-56b201caf064)

MODEL GRAPH
 <img width="919" height="1290" alt="image" src="https://github.com/user-attachments/assets/55326c5b-7dd5-4873-aaf6-d219bb7c4420" />

 
 


RESULT:
Thus the amplitude modulation and demodulation is experimentally done and the output is verified.
