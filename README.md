# SPI_Serial_Peripheral_Interface_Verilog_Modules
Implementation of a Serial Peripheral Interface(SPI) using Verilog and testing various modes of the SPI Device

<strong>Simulated & Verified using Vivado

 The objective of this project was to gain hands-on experience in designing and implementing digital circuits using Verilog, as well as to gain a deeper understanding of the SPI protocol and its applications. 


<strong>SPI MASTER CORE ARCHITECTURE & DESIGN BLOCKS OF SPI MASTER CORE ARCHITECTURE</strong>

<p align="center">
  <img src="">
</p>

Features of SPI Master Core Include Full duplex synchronous serial data, Variable length of transfer word up to 128 bits, MSB or LSB first data transfer, Rx and Tx on both rising or falling edge of serial clock independently, Up to 32 slave select lines, Auto Slave Select, Interrupt Enable & Clock Divider.

To meet specific system requirements and size constraints on behalf of the functionality, the SPI Master core can be configured by setting the appropriate define directives in the “spi_defines.v” source file.

