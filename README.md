# Simulation-of-CMOS-based-Comparator

## Abstract
With increase in portable battery and mobile devices like iot internet of things and smart gadgets , it become design
requirement of low power, low voltage, low noise, High speed and high performance. The growing demand of
performance and efficiency is achieved by continuous advancement and development of CMOS technology.
Comparator being most essential component of Analog Digital convertor, its designing become crucial and
critical. This paper present the review of several design aspect of comparator like performance, power and delay.
Comparator is designed and simulated using open source SPICE simulator.

## Reference Circuit Details
The dynamic latch comparator shown in figure is most widely used because it has many advantages such as high-speed, zero static-power consumption, 
high input-impedance and fullswing output. During the pre-charge phase both the output nodes are charged to power supply voltage and 
during the evaluation phase the output of the comparator depends on the differential input.
The latch will amplify the difference between input signals after the output of the latch will be in digital level. comparator with needs a high accuracy clock.
The preamplifier is consist of two PMOS transistors and three NMOS transistors. Two input signals are
applied at NM1 and NM2 transistor in common mode and differential mode to get the gain circuit detects
the differential voltage output. The dynamic latch circuit consists of 4 PMOS transistors and 5 NMOS transistors.
The input of this dynamic latch is output of preamplifier circuit. The output of the preamplifier are
connected to the NM6 and NM7.
The main drawback of this comparator is it consists of only one tail current transistor M11 which is used to control the currents flowing through both the differential 
input pair (M10 and M5) and the latch (M3,M4,M8,M9). The size of the tail transistor M11 should be increased to increase the drive currents of the latch. 
But, if we increase the size of the tail transistor M11.
