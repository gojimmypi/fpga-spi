
This is a simple SPI slave device for FPGAs. The project file is for a Lattice iCEblink40 development board.
The STM32 test driver is for an STM32F103 ARM microcontroller.


Add fpga-spi.ys, ulx3s_v20.lpf and Makefile

include "spi.v" in spi_driver.v

https://courses.cs.washington.edu/courses/cse466/11au/calendar/07-comms-posted2.pdf