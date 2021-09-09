# Connections

![image](https://user-images.githubusercontent.com/56167642/132639594-19401470-450c-42ba-b157-1615b3268123.png)

![image](https://user-images.githubusercontent.com/56167642/132639348-2126c85a-19e2-4be0-83a1-0c67c58d9cf6.png)

The LDR gives out an analog voltage when connected to VCC (5V), which varies in magnitude in direct proportion to the input light intensity on it. That is, the greater the intensity of light, the greater the corresponding voltage from the LDR will be. Since the LDR gives out an analog voltage, it is connected to the analog input pin on the Arduino. The Arduino, with its built-in ADC (analog-to-digital converter), then converts the analog voltage (from 0-5V) into a digital value in the range of (0-1023). When there is sufficient light in its environment or on its surface, the converted digital values read from the LDR through the Arduino will be in the range of 800-1023.
