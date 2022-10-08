# Flash-type-ADC
It is the Flash type Analog signals into digital converter
Flash Type ADC
Mr.V.Karuppusamy

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

![image](https://user-images.githubusercontent.com/105380792/194703412-98825997-b0ad-42eb-9dce-3e8048106d0f.png)
![image](https://user-images.githubusercontent.com/105380792/194702877-585921a5-3497-4916-aed5-f7d616e29eed.png)




 Fig1 : Flash type ADC Converter
 3.IMPLEMENTED WAVEFORMS
 ![image](https://user-images.githubusercontent.com/105380792/194702890-866187bd-9fca-4da4-b38e-223f7b218026.png)

     

 Fig2 : Reference circuit input waveform
 ![image](https://user-images.githubusercontent.com/105380792/194702912-d8bd4c06-d354-46cf-bf3b-c37909946c4a.png)
![image](https://user-images.githubusercontent.com/105380792/194702931-3013b35d-5ec6-44e3-86bc-42434072747f.png)
![image](https://user-images.githubusercontent.com/105380792/194702941-f0230bb9-9cd0-4e6a-abc9-8f3953896c7f.png)


 
 Fig3 : Reference circuit 3-bit output digital waveform

References :
[1]	Mishra, S., Vidyarthi, A. and Akashe, S., 2013, April. A novel folding technique for 3 bit flash adc in nanoscale. In 2013 Third International Conference on Advanced Computing and Communication Technologies (ACCT) (pp. 307-311). IEEE.
