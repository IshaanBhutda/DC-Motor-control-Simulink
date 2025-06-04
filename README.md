# DC-Motor-control-Simulink
An asynchronous motor was controlled by powering it with a DC voltage passed through 6 IGBT diodes, inverting the voltage to 3 phase AC voltage with 120 degree phase difference.

We are controlling the speed of the motor using a PID controller and by feeding in the desired rpm as a step input. Based on that, gate pulses are created which are sent to the IGBT diodes from which the voltage supplied is controlled causing speed of the motor to change. 
