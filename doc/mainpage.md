\brief		RSVP-SIS : Reference System Virtual Platform
\details	A library for small virtual emmbedded platforms. 
\author		Tom Moxon
\copyright	PatternAgents, LLC
\mainpage	RSVP-SIS Documentation
\section	main_intro Introduction
\par
RSVP-SIS is an open source library for creating simple embedded microcontroller platforms. \n
 \n
\par
\section	main_background Background
\par
 \n
\par
RSVP-SIS was developed to provide a simple interface for transportable embedded applications. \n
The RSVP-SIS platforms come with all components supported with Interrupt Service Routines (ISRs),
and stream buffers (channels). Channels can be simply wired together to create bridge functions.
Auotmatically generated APIs (based on the instance name) are utilized for the majority of
low level components, and are availble to be used by the application.
\n
\par
\section	main_overview RSVP-SIS CLI Overview 
\par
The RSVP-SIS command line interface (CLI) uses familiar text commands \n
\n
For example :\n
> \>test adc\n
(reads out all adc values)

> \>test led\n
(blinks all leds)

> \>test uart\n
(outputs a string to all uart ports)

> \>test boot\n
(starts the bootloader program)

> \>wire 1 3\n
("wires" UART1 to UART3)

\par

\section	main_installation RSVP-SIS Install Instructions 
\par
\defgroup main_commands RSVP-SIS Command Definitions
@{
@}


