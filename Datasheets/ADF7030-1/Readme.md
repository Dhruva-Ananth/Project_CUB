[ADF7030-1 Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/adf7030-1.pdf)

[ADF7030-1 Website](https://www.analog.com/en/products/adf7030-1.html)

[ADF7030-1 Hardware Design Manual](https://www.analog.com/media/en/technical-documentation/user-guides/ADF7030-1-UG-957.pdf)

[ADF7030-1 Software Design Manual](https://www.analog.com/media/en/technical-documentation/user-guides/ADF7030-1-UG-1002.pdf)

System Design
-----------------------------------------------------------------------------------------------
Chosen Center Frequency - 437MHz (Channel Freq Resolution 1.5Hz)
Sesitivity -> -104dBm @4.8kbps (IDEAL -> -121.2dBm @2.4kbps)
Modulation -> 2FSK (IEEE802.15.4g Packet Mode)(Deviation - 1KHz to 250KHz/ Resolution 100Hz)
Operational Temperature - -40C to +85C
Transmit Power(from PA2) -> 


Schematic Design
-----------------------------------------------------------------------------------------------
Power supply - 2.2V-3.6V -(Typical support -3V)
SPI Interface(host Processor) - 4lines
26MHz Crystal Osciallator (OR) 26MHz TCXO can be DC coupled to HFXTALN pin  - Desision -> PENDING



PCB Design
-----------------------------------------------------------------------------------------------
Packaging - 40Lead - LFCSP (@460MHz Differential LNA Impedance -> Rx mode -> 68-j25)
LNAIN1 and LNAIN2 are ac-coupled
LNA Rx Impedance -> 68.5-j25 Ohms
PA2 Tx Impedance -> 38+j25 Ohms

Specialities
-----------------------------------------------------------------------------------------------
-> Available Ultralow Power Deep Sleep mode -10nA
-> Smart Wake mode, using internal RTC
-> Auntonomous operation triggered from Interrupt of host processor
-> Fine Adjustement of the Dual Power amps (Ideal for Adaptive design)
-> Digital recieved sense Indicator
