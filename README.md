# Kestrel
A enhanced follow-up for Raven68k board.

Planned features are as follows;
- 68020 CPU with 68881 FPU possibly
- 64kB EEPROM for system firmware
- Single 72pin SIMM slot for system RAM, maximum still undecided.
- Dallas DS12887A RTC for time and system settings
- Xilinx XC9572XL or bigger CPLD as system glue logic.
- A system expansion bus with;
  - OPL2 or OPL3 based soundcard
  - Mass storage card with IDE and floppydrive
  - An I/O card with 68681 DUART with USB adapter on one UART and max233 on other port and a Centronics port.
  - A graphics card. Either a simple 6847 based one or a simple framebuffer type of thing made with a CPLD.
  - An RTL8029A based Ethernet card
- Some I/O for using a keyboard etc. 

Specifications are subject to change, even radically, until they are to be nailed down as the design goes forward

