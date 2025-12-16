# OP-AMP
## REG NUM :Surjini.R
## NAME :25015534
## EPERRIMENT NO 5: Design a CMOS Operational Amplifier and find out the AC analysis.
## Aim:
To design a CMOS Operational Amplifier and find out the AC analysis.

## Tools Used:	
Virtuoso Schematic Editor is used for the design and analysis.

## Theory:
An operational amplifier (or an op-amp) is an integrated circuit (IC) that operates as a voltage amplifier. An op-amp has a differential input. That is, it has two inputs of opposite polarity. An op-amp has a single output and a very high gain, which means that the output signal is much higher than input signal. These amplifiers are called "operation" amplifiers because they were initially designed as an effective device for performing arithmetic operations in an analog circuit. The op-amp has many other applications in signal processing, measurement, and instrumentation

## Procedure:
•	Click  new -> library attach to an existing technology library gpdk180(in technology file )
•	New cell view(name of the layout)
## For Schematic:
a.)TRANSISTOR DIAGRAM:
<img width="302" height="227" alt="OPAMP DIA" src="https://github.com/user-attachments/assets/564b32f0-5f22-4ad7-becf-c05b5e248acc" />

Fig: Operational amplifier Transistor schematic


B.)IN CADENCE:
•	Pick the components NMOS, PMOS, ground, VDD and voltage source.
•	Connect the wire as per the schematic diagram.

<img width="880" height="496" alt="image" src="https://github.com/user-attachments/assets/6461df3e-b547-4859-b400-c3328252db56" />

Fig: Operational amplifier schematic

AC Analysis:
a)	In the Analysis section, select ac.
b)	Define pulses pecificationas
c)	AC Magnitude= 1; DC Voltage= 0; Offset Voltage= 0; Amplitude= 5m; Frequency= 1K
d)	In the "Sweep Range", sweep from 150 to100M. In "Sweep Type", choose" Logarithmic" and enter a "Step Size" of 20 decade.
e)	Check the enable button and then click Apply.
f)	Click OK in the Choosing Analyses Form.


## Execute Outputs:
To be plotted – Select on Schematic in the simulation window. 
Follow the prompt at the bottom of the schematic window, 
Click on output net Vref vs Vout in the schematic. 

## Execute Simulation:
Net list and Run in the simulation window to start the Simulation.
When simulation finishes, the DC, AC plots automatically will be popped up along file.

## Waveforms:
<img width="975" height="493" alt="image" src="https://github.com/user-attachments/assets/ad189648-de75-46e7-abc9-c7ff371b9475" />


## RESULT:
The Design a CMOS Operational Amplifier and find out the AC analysis is performed.




