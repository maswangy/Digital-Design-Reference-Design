Introduction:
Bluetooth_IP uses the UART protocal.

Parameters: 
DVSR = clk/(baunds*16)is the abbreviation of Divisor Values of Send Rate.

Ports' describtion:
clk: clock of system
reset: reset of system
rx: port of receiver
tx: port of transmitter
data_out: 8-bits output data
	
data_in: 8-bits input data
tx_btn: control of transmitter,connected with a button
rx_done: signal of data receiving success
tx_done: signal of data transmitting success