Introduction:
 This IP has two parts. One is the transmitter, another is 
receiver. Transmitter is used for send out the data in shift-register one bit by one bit according to the certain rate.The receiver is 
opposite.

Parameters: 
DVSR = clk/(baud rate*16)is the abbreviation of Divisor Values of Send Rate.

Ports' description:
clk: system clock
reset: system reset
rx: port of receiver
tx: port of transmitter
data_out: 8-bits output data
	
data_in: 8-bits input data
tx_btn: control of transmitter,connected with a button
rx_done: signal of data receiving success
tx_done: signal of data transmitting success