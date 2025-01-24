Audio Spectrum Visualizer

Samples stereo analog audio and displays the frequency response on an 8x24 dot LED display.

Inputs:
USB-C PD

R/L RCA at audio line level


USB-C comes in at 20V. 
Supply rails:
3.3V digital supply
5V display supply
+/-6V analog supplies. +/-5V after LDO

R/L RCA has two identical channels
Gain stage
Unity gain stage to add offset (0-5V signal)
Anti Aliasing Low Pass Filter stage
Sampled using ADC121S101 over SPI

Digital Section is anything in the Arduino Nano pinout/form factor. Going with an STM32 NUCLEO-L432KC

Nucleo drives LEDs using I2C to three HT16K33A (borrowing architecture from Adafruit). 

Includes rotary encoder for brightness control and pushbutton.