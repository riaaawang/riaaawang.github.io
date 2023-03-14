Introduction:

The objective of this lab was to gain familiarity with programming the Sparkfun Artemis by setting up the Arduino IDE and running example code to test basic functionality. This report details the four examples that were completed during the lab, including Blink, Serial, Analog Read, and Microphone Output.

Example 1: Blink It Up

The first example involved testing the LED on the Artemis board by blinking it using the "Blink" example from the Arduino IDE. The LED_BUILTIN pin in the code was mapped to the correct pin on the Artemis. A 1-second on and 1-second off pattern was used to confirm the basic functionality of the LED.

Example 2: Serial

The second example involved running the Artemis Serial example code to test the serial port. The baud rate was set to 115200. The serial monitor was used to confirm that the text typed in was echoed back, indicating that serial communication was functioning properly.

Example 3: Analog Read

The third example involved using the Artemis Analog Read example code to read the onboard temperature sensor. The temperature reading began at approximately 31,800 and increased to over 32,000 when the sensor was exposed to the heat release vent of a laptop, confirming the functioning of the sensor and the analog-to-digital converter (ADC).

Example 4: Microphone

The fourth and final example involved testing the onboard microphone. The Microphone Output example code was used to print out the loudest frequency after performing a fast Fourier transform (FFT). The highest frequency ranged from 0 to about 200 due to ambient noise, but when a beep was played, the frequency consistently hit 1007.

Conclusion:

In conclusion, this lab provided a useful introduction to programming the Sparkfun Artemis. By completing the four examples, we gained familiarity with basic functionality such as serial communication, analog readings, and microphone output. These skills will be useful in future labs as we continue to develop our knowledge of robotics and programming.