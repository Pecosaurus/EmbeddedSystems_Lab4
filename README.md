# EmbeddedSystems_Lab4

# In this Lab, we are utilizing different different Timers and PWM on the MSP430FR2355 to toggle the output of different pins on the board. 

# In the first part of the lab, we utilized the Watch Dog Time to Toggle the Green LED, Pin p6.6, every 250 ms. This is done using the interrupt process of the board.    The purpose of this code is to learn how to use the WDT as the interval timer to turn the LED on or off or the input current of a pin on or off. Another purpose of the is to utilize the built in shortcut in the IDE to assign the values of the different setting description fields of the WDT to what kind of time interval you want the WDT to output in the board without type each setting field.

# In the second part of the lab, we utilized the Pulse Width Modulation (PWM) with one of the onboard clocks to turn the current or power to a pin on the board for a certain portion of a wave period and off for the rest of the period using a duty cycle percentage. The Polling processes was used, which programs how the computer reacts to the PWM time signal to turn on and off the pin on the board. The purpose of this code and this exercise is to utilize and understand how to program to PWM to work with one of the clocks, which the Auxiliary Clock was used in my code, to make the pulsing time signal. Also, we learned how to calculate the PWM Period and PWM duty cycle using formulas with the desired duty cycle percentage, period of each signal, and the frequency of the clock utilized. We also learned and got experence figuring out the difference Timer setting we need to set to make the PWM work correctly for our desired PWM impulse signal we want to create.

# In the third part of the lab, we do the same concept as the code in part two except the interrupt process of the board is used. The purpose of this exercise is to see how the PWM and the toggling of the pin output power is coded different between the polling process and the interupt process and what setting of the PWM need to be set for each process.
