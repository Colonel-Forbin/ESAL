# ADC Lab

#### Prelab

Read Chapter 13 of the TM4C123 data sheet on the Analog to Digital Converter    
Read Analog to Digital Converter portion of the TivaWare Peripheral Driver Library User's Guide

#### Lab

Connect at minimum 2 slide pots, 2 regular pots 2 analog sensors to your board.

Create a C file called ADC_helper.c and a header file called ADC_helper.h

In ADC_helper.h create a function that returns a void and passes in a void.  Call the function ADC_setup.  It will look like this

	void ADC_setup (void) ; 

In the Gpio_helper.c file include the header file and make start the function.  It should look like this

	#include "Gpio_helper.h"

	//This function sets up ADC pins
	void ADC_setup()
	{
		//code here.
	} 

Add the files to the your project appropriately and make sure it compiles.  

In the ADC_setup function, initialize and setup your ADC lines.  Consult data sheet and peripheral driver library to help you.   

read in the ADC values and print them to the screen in Volts.  Check your accuracy with a Volt meter.  Print the value of the sensor to the screen as well, not the voltage.  Ie.  If it is a presure sensor and you are putting 1N of force on it, make sure it displays 1N of force.  

Save your code, commmit it, push to github when documented.  