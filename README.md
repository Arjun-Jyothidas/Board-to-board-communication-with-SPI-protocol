Following repository contains HAL C codes for developing a SPI communication between two boards - a master board and a slave board.
Only the main source files are added in this repository as the rest of the files are generated automatically by the STMCubeIDE.
Both the main .c files for respective master and slave board is included in the repository.
The target microcontroller - STM32U545RE-Q is selected in the STMCubeMX, matching the hardware.
The following repository shows that master sends the transmitting data to the slave through SPI communication.
Received data then, transmitted through UART and the output obtained in the Serial Console.
