# STM32-gas-sensor-and-temperature-measurement

This is my project for integrated circuits and microprocessors. Based on STM32 microcontroller I have built system 
for internal processor temperature and gas concentration measurement. Results are presented on 16x2 LCD. The communication 
between PC and MCU is assured by serial interface USART with interrupts and ring buffer. The communication between MCU and LCD 
is based on I2C serial interface. To get analog data from sensors I operated on two ADC channels with DMA mechanism to pull data 
directly from ADC registers to PC memory.
