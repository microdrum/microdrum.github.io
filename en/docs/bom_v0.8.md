---
title: Bill Of Materials v0.8
lang: en
---
The following electronic component links point to the Mouser reseller.
Obviously you can buy them elsewhere.
Some alternatives are included where possible in case there are stock or
availability issues for the main parts.

## Mainboard v0.8

| Part            | Qty | Description                                                      | Manufacturer Part No
| --------------- | --- | ---------------------------------------------------------------- | -----------
|                 |     |                                                                  | **Circuit Board**
| PCB             | 1   | Mainboard v0.8                                                   | [microDrum Store](http://microdrum.net/blog/products-page-2/pcb/microdrum-pcb-v0-8-fundraising-duplicate/)
|                 |     |                                                                  | **Arduino**
| Uno             | 1   | Will need Mainboard set to 5V version                            | [A000066](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey782-A000066)
| Due             | 1   | Will need Mainboard set to 3.3V version                          | [A000062](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey782-A000062)
|                 |     |                                                                  | **Teensy**
| Teensy 3.2      | 1   | **Not tested**                                                   | [DEV-13736](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey474-DEV-13736) SparkFun
|                 |     |                                                                  | **Resistors**
| R1-R6           | 6   | 1 MOhm, 1%, 0.25W                                                | [271-1.0M-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-1.0M-RC) Xicon
| R7-R8-R18       | 3   | 10 KOhm, 1%, 0.25W                                               | [271-10K-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-10K-RC) Xicon
| R9-R10          | 2   | 68 Ohm, 1%, 0.25W                                                | [271-68-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-68-RC) Xicon
| R11             | 1   | 100 KOhm, 10%, 0.5W Trimmer                                      | [3362F-1-104LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey3362F-1-104LF) Bourns
| R12             | 1   | 1.5 KOhm, 1%, 0.25W                                              | [271-1.5K-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-1.5K-RC) Xicon
| R13-R14         | 2   | 220 Ohm, 1%, 0.25W                                               | [271-220-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-220-RC]) Xicon
| R15             | 1   | 3.3 KOhm, 1%, 0.25W                                              | [271-3.3K-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-3.3K-RC) Xicon
| R16-R17         | 2   | 1 KOhm, 1%, 0.25W                                                | [271-1K-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-1K-RC) Xicon
| RLED            | 1   | Depends on led type                                              | Xicon 271 range
|                 |     |                                                                  | **Capacitors**
| C1-C2           | 2   | 22 pF                                                            | [1C10C0G220J050B](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey75-1C10C0G220J050B) Vishay
| C3-C4-C5        | 3   | 10 uF                                                            | [ECE-A1HKA100B](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey667-ECE-A1HKA100B) Panasonic
|                 |     |                                                                  | **Switches**
| 5V/3.3V         | 1   | SPDT (See build details for purpose of these switches)           | [MS12AFG01](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey633-MS12AFG01) NKK
| Jumper          | 1   | 1 x 2 shorting jumper (Could just use wire if will never change) | [63429-202LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-63429-202LF) Amphenol FCI, [929951-00](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-951-00) 3M, [M7582-46](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M7582-46) Harwin
|                 |     |                                                                  | **Crystal**
| XTAL            | 1   | 16 MHz                                                           | [LFXTAL058383Bulk](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey449-LFXTAL058383BULK) IQD
|                 |     |                                                                  | **Diodes**
| D1-D2           | 2   | 1N5227 Zener 3.6V                                                | [1N5227BTR](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey1N5227BTR) ON / Fairchild
| D3              | 1   | 1N4148                                                           | [1N4148TR](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey78-1N4148) Vishay, [1N4148TR](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey512-1N4148TR) ON / Fairchild
| LED             | 1   | Green Led                                                        | [350-00001](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey350-00001) Parallax
|                 |     |                                                                  | **ICs**
| IC1-IC6         | 6   | SN74HC4851 (each 1 = 8 ports)                                    | [SN74HC4851N](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey595-SN74HC4851N) Texas Instruments
| IC7             | 1   | SN74HC595 Shift Register                                         | [SN74HC595NE4](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey595-SN74HC595NE4) Texas Instruments
| IC8             | 1   | 7805                                                             | [TL780-05KCS](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey595-TL780-05KCS) Texas Instruments
| 6N138           | 1   | 6N138                                                            | [6N138](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey782-6N138) Vishay, [6N139M](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey512-6N139M) ON / Fairchild
| ATtiny4313      | 1   | ATtiny4313                                                       | [ATTINY4313-PU](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey556-ATTINY4313-PU) Microchip
|                 |     |                                                                  | **Transistor**
| BC547           | 1   | BC547BTA                                                         | [BC547BTA](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey512-BC547BTA) ON / Fairchild
|                 |     |                                                                  | **Sockets**
| IC1/IC6/IC7skt  | 7   | 16 pin DIP (2x8)                                                 | [DILB16P-223TLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-DILB16P-223TLF)  Amphenol FCI, [4816-3004-CP](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-4816-3004-CP) 3M
| 6N138skt        | 1   |  8 pin DIP (2x4)                                                 | [DILB8P-223TLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-DILB8P-223TLF) Amphenol FCI, [4808-3004-CP](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-4808-3004-CP) 3M
| ATtiny4313skt   | 1   | 20 pin DIP (2x10)                                                | [DILB20P-223TLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-DILB20P-223TLF) Amphenol FCI
|                 |     |                                                                  | **Connectors**
| J1-J6           | 6   | 2 x 5 header                                                     | [67997-410HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-67997-410HLF) Amphenol FCI, [XG8W-1041](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG8W-1041) Omron, [M20-9760546](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9760546) Harwin
| MIDI In/Out/Aux | 3   | 5 pin DIN socket                                                 | [NYS325](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey568-NYS325) REAN / Neutrik, [T3359-150](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey523-T3359150) Amphenol
| Header          | 2   | 1 x 36 header - split (will cover all headers)                   | [929834-02-36-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-36-RK) 3M
| Arduino2 Header | 1   | 2 x 13 header                                                    | [67996-236HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-67996-236HLF) Amphenol FCI

## Jack Board v0.4

These quantities are for a single board, giving you 4 sockets.

| Part     | Qty | Description                                                      | Manufacturer Part No
| -------- | --- | ---------------------------------------------------------------- | --------------
|          |     |                                                                  | **Circuit Board**
| PCB      | 1   | Jack Board v0.4                                                  | [DIY](/downloads/microDRUM_Jack_v0.4-PCB.pdf)
|          |     |                                                                  | **Jacks**
| U1-U4    | 4   | Mono sockets for single piezo trigger, stereo for two            | Stereo: [NMJ6HFD2](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey550-20301), [NRJ6HF-1](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey550-20384) or Mono: [NMJ4HHD2](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey568-NMJ4HHD2) Neutrik
|          |     |                                                                  | **Resistors**
| R1-R4    | 4   | 1 MOhm or 100 Ohm with HHC Resistor; 1%, 0.25W                   | Xicon 271 range
|          |     |                                                                  | **Switches**
| S1-S4    | 1   | 1 x 12 header                                                    | [929834-02-12-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-12-RK) 3M
| Jumper   | 4   | 1 x 2 shorting jumper (Could just use wire if will never change) | [63429-202LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-63429-202LF) Amphenol FCI, [929951-00](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-951-00) 3M, [M7582-46](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M7582-46) Harwin
|          |     |                                                                  | **Connectors**
| Conn1    | 1   | 2 x 5 header                                                     | [67997-410HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-67997-410HLF) Amphenol FCI, [XG8W-1041](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG8W-1041) Omron, [M20-9760546](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9760546) Harwin
|          | 1   | 2 x 5 socket                                                     | [65239-005LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65239-005LF) Amphenol FCI, [XG4M-1030](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG4M-1030) Omron, [M20-1070500](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-1070500) Harwin
| Contacts |     | To fit 22-30 AWG wire (assuming that matches ribbon wire above)  | [76347-401LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-76347-401LF) Amphenol FCI, [08-50-0114](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-08-50-0114) Molex - Need to make sure compatible with sockets chosen
| Wire     |     | Ribbon cable, rainbow version optional…                          | Ebay is best option as Mouser only does long lengths
