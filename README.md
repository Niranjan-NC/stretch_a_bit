Select an RC low pass filter circuit to produce a variable analog voltage from a resistor and capacitor. With a pulse voltage of 5V amplitude, the capacitor is connected in parallel to the resistor. LT spice schematics are attached in this.
1. The resistor and capacitor values for the first example are 10K ohm and 0.1uF, respectively. 
PWM duty cycles are varied by 25%, 50%, 75%, and 100% from the pulse voltage source by changing the "Ton" value to vary duty cycle.
The predicted result and the voltage difference are shown as "Draft1.jpg" and "Draft1_voltage.jpg," respectively, in the attachments.
2. In the following example, the resistor is 70K ohms in value and the capacitor is 5nF.  PWM duty cycles are varied by 25%, 50%, 75%, and 100% from the pulse voltage source by changing the "Ton" value to vary duty cycle. The predicted result and the voltage difference are shown as "Draft2.jpg" and "Draft2_voltage," respectively, in the attachments.

The input voltage to the RC low pass filter will be a sequence of short, low-voltage triangle pulses for a 25% duty cycle. PWM signal is high half the time and low half the time for a 50% duty cycle. A sequence of lengthy, generally high pulses will be the input voltage to the RC low pass filter for a 75% duty cycle. When the duty cycle is 100%, the low pass filter will have a constant voltage that is the same as the PWM high voltage. 

I'm sorry to inform that I was unable to run this in Python since I was unable to install the necessary peripherals for LTSpice. I made numerous attempts to fix the problem, but it was impossible. Either my system has a flaw, or I made a mistake that I was unable to correct. 
