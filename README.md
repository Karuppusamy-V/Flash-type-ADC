# Flash-type-ADC
It is the Flash type Analog signals into digital converter
Flash Type ADC
Mr.V.Karuppusamy
(karuppusamy.ec21@bitsathy.ac.in)
Bannari Amman Institute of Technology
 08 October 2022

 
 
 
 
Abstract— Generally, in our daily applications we experience analog to digital converters. Analog to digital converters (ADCs) are used in high bandwidth applications such as communications, radar processing, satellite communications, and data acquisition system. So, we design and optimized the low-power and high-speed 3-bit flash Analog-to-Digital Converter (ADC) using sky130 technology. High-integrated flash ADC is designed at three-bit precision.
Keywords—Flash adc, Priority encoder, comparator.
1.	REFERENCE CIRCUIT DETAILS
As shown in the figure have entire topology of a Flash type analog to digital converter. Which consists of sine wave as the analog input source for in1 and 1v dc source used as a constant voltage reference for in2. 
 Eight avsd operational amplifiers, sky130 resistors, and ADC bridge are used in our circuit
And Priority encoder has been interfaced to translate analog or linear signals into a digital signals.
The main advantages are the construction is simple and easier to design and it is the fastest type of ADC because it produces an equivalent digital output for a corresponding input in no time and time required for the typical conversion is less.
2.	IMPLEMENTED CIRCUIT





 Fig1 : Flash type ADC Converter
       3.IMPLEMENTED WAVEFORMS
       ![image](https://user-images.githubusercontent.com/105380792/194702760-ff36ef58-4baf-4c98-917f-6cc8e673e66b.png)


 Fig2 : Reference circuit input waveform
 ![image](https://user-images.githubusercontent.com/105380792/194702789-019fb02e-bb2e-4c3c-b9bf-6c1a567a1120.png)
 ![image](https://user-images.githubusercontent.com/105380792/194702812-e0b8a8c9-f7c0-4671-bc67-7606da5c4c8e.png)
![image](https://user-images.githubusercontent.com/105380792/194702819-1bc42633-8984-4330-843b-d614fb275c1a.png)

     Fig3 : Reference circuit 3-bit output digital waveform

References :
[1]	Mishra, S., Vidyarthi, A. and Akashe, S., 2013, April. A novel folding technique for 3 bit flash adc in nanoscale. In 2013 Third International Conference on Advanced Computing and Communication Technologies (ACCT) (pp. 307-311). IEEE.
