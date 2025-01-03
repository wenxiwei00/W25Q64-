# W25Q64-
STM32F103C8T6
硬件实现SPI外设，首先要看library里面的SPI外设库，stm32f10x_spi.h
![image](https://github.com/user-attachments/assets/7cea681e-cf8d-4893-b6d9-267f9d23f2af)
SPI_Init：SPI的初始化
SPI_StructInit：SPI的结构体初始化
SPI_Cmd：SPI外设初始化
SPI_I2S_SendData：写数据到发送缓冲区TDR
SPI_I2S_ReceiveData：把要读的数据写到接收缓冲区RDR
FlagStatus SPI_I2S_GetFlagStatus：用来获取TDR是否有东西的标志位TXE，RDR是否有东西的标志位RXNE
