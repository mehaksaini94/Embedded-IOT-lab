# Link for downloading Arduino IDE
https://www.arduino.cc/en/software

# Arduino Uno board
![image](https://user-images.githubusercontent.com/56167642/132465388-8aab246b-ef9b-4cd0-86fa-940f471bacf8.png)
# Arduino Uno pin description
Vin: This is the input voltage pin of the Arduino board used to provide input supply from an external power source.

5V: This pin of the Arduino board is used as a regulated power supply voltage and it is used to give supply to the board as well as onboard components.

3.3V: This pin of the board is used to provide a supply of 3.3V which is generated from a voltage regulator on the board

GND: This pin of the board is used to ground the Arduino board.

Reset: This pin of the board is used to reset the microcontroller. It is used to Resets the microcontroller.

Analog Pins: The pins A0 to A5 are used as an analog input and it is in the range of 0-5V.

Digital Pins: The pins 0 to 13 are used as a digital input or output for the Arduino board.

Serial Pins: These pins are also known as a UART pin. It is used for communication between the Arduino board and a computer or other devices. The transmitter pin number 1 and receiver pin number 0 is used to transmit and receive the data resp.

External Interrupt Pins: This pin of the Arduino board is used to produce the External interrupt and it is done by pin numbers 2 and 3.

PWM Pins: This pins of the board is used to convert the digital signal into an analog by varying the width of the Pulse. The pin numbers 3,5,6,9,10 and 11 are used as a PWM pin.

SPI Pins: This is the Serial Peripheral Interface pin, it is used to maintain SPI communication with the help of the SPI library. SPI pins include:

SS: Pin number 10 is used as a Slave Select
MOSI: Pin number 11 is used as a Master Out Slave In
MISO: Pin number 12 is used as a Master In Slave Out
SCK: Pin number 13 is used as a Serial Clock
LED Pin:  The board has an inbuilt LED using digital pin-13. The LED glows only when the digital pin becomes high.

AREF Pin: This is an analog reference pin of the Arduino board. It is used to provide a reference voltage from an external power supply.

# Basic Arduino commands
Serial.println(value):  Prints the value to the Serial Monitor on your computer

pinMode(pin, mode): Configures a digital pin to read (input) or write (output) a digital value

digitalRead(pin): Reads a digital value (HIGH or LOW) on a pin set for input

digitalWrite(pin, value): Writes the digital value (HIGH or LOW) to a pin set for output

The Arduino reference for digitalRead: http://arduino.cc/en/Reference/DigitalRead

The Arduino reference for digitalWrite: http://arduino.cc/en/Reference/DigitalWrite

The Arduino reference for pinMode: http://arduino.cc/en/Reference/PinMode

The Arduino references for constants (HIGH, LOW, etc.): http://arduino.cc/en/Reference/Constants

Refer the following link for understanding Arduino IDE functions:
https://www.arduino.cc/reference/en/
