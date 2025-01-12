# Exidy Sorcerer FPGA replica

The Sorcerer is a home computer system released in 1978 by the video game company Exidy.

### Tape Loading

Loading real tapes are supported (using UART_RX on MiST or the Audio input port on SiDi).
A collection of WAV files can be found at https://www.classic-computers.org.nz/blog/2017-01-23-software-for-real-sorcerers.htm

Looks like 1200 baud files are not working, I'm not sure about the issue, but it seems the Monitor doesn't read the incoming data
fast enough, indicated by "Overrun" in the UART.

(C) 2024 Gyorgy Szombathelyi

T80 Copyright (c) 2001-2002 Daniel Wallner and others

