# Device Drivers for STM32f10
 Full Software Interfaces for STM 32(ARM Cortex-M3) peripherals and Implemented simple hardware applications.
 The repo consists of folders where each one represents a layer in a layered software architecture.
 - Note: All layers are horizontal except OS and LIB layers (vertical).
 
 ## Layers:
 
 ### Implemented Layers:
 
 #### MCAL (Microcontroller abstraction layer):
 1- RCC (Reset and control clock).
 2- NVIC (Nested vector interrupt controller).
 3- STK (Systick timer).
 4- GPIO (General purpose I/O).
 5- DMA (Direct memory access controller).
 6- FLASH.
 7- USART Supporting two modes:
	a) Reception and Transmission using DMA Mode.
	b) LIN (local interconnection network) Mode.
 
 #### HAL (Hardware abstraction layer):
 1- LED_Handler.
 2- Switch_Handler.
 3- Lcd_Handler.
 4- STK_Handler.
 5- USART_Handler.
 6- LIN_Handler.
 
 #### APP (Application layer):
 - Contains some application codes and examples.
 
 #### LIB (Library layer):
 1- STD_TYPES.
 2- BIT_MATH.
 3- DELAY.
 4- STRING.
 
 #### OS (Operating system):
 - Contains a Task Scheduler code.
 
 ### NOT implemented layers:
 These layers are yet to be implemented and added in the future:
 - SRV (Service).
 - MEM (Memory).
