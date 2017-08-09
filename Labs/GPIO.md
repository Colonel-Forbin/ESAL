# GPIO Lab

Connect at minimum 2 momentary switches, 2 toggles switches and 4 LEDs to your board.

Create a C file called Gpio_helper.c and a header file called Gpio_helper.h

In Gpio_helper.h create a function that returns a void and passes in a void.  Call the function Gpio_setup.  It will look like this

	void Gpio_setup (void) ; 

In the Gpio_helper.c file include the header file and make start the function.  It should look like this

	#include "Gpio_helper.h"

	//This function sets up GPIO pins
	void Gpio_setup()
	{
		//code here.
	} 

Add the files to the your project appropriately and make sure it compiles.  

In the Gpio_setup function.  Initialize your gpio.  You can look at example projects to figure it out.  This well help you with code reading skills. 

In your main.c create a function called "LED display".  Create some behavior that uses the buttons to control the LEDs.  and make sure to describe it in the comments.

Next create a file named Uart_helper.c and Uart_helper.h and add them to your project.  Name the functions appropriately. Print the status of the buttons and leds to the screen approximately 2 times a second.  Save your code, commmit it, push to github when documented.  