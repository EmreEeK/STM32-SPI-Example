# STM32 SPI Example
 STM32_Nucleo---STM32_Discovery   SPI communication. Discovery board's pins were represent four different slaves
 
 STM32_Nucleo board will send a simple byte that hold either 11 or 22 (decimal). When slave (STM32_discovery) receive both select signal (Master's gpio out pins) and byte value. It will switch between cases and slaves.
