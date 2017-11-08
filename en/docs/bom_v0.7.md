---
title: Bill Of Materials v0.7
lang: en
---
This list of hardware parts focuses on Mouser part numbers, as the most commonly
used online electronics store. You can of course get the manufacturer's part
number from there and buy elsewhere! Alternatives are included where possible
in case there are stock or availability issues for the main parts.

## Mainboard v0.7

| Part              | Qty | Description                                                                     | Manufacturer Part No                                                                            | Alternatives |
| ----------------- | --- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------ |
|                   |     |                                                                                 | **Circuit Board**
| PCB               | 1   | Mainboard v0.7                                                                  | [DIY](/downloads/microDRUM_v0.7-PCB.pdf)
|                   |     |                                                                                 | **Arduino**
| Uno               | 1   | Will need Mainboard set to 5V version                                           | [A000066](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey782-A000066) | EBay
| Due               | 1   | Will need Mainboard set to 3.3V version                                         | [A000062](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey782-A000062) | EBay
|                   |     |                                                                                 | **Resistors**
| R1-R6             | 6   | 1 MOhm, 1%, 0.25W                                                               | [271-1.0M-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-1.0M-RC) Xicon  | [MF1/4DCT52A1004F](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey660-MF1-4DCT52A1004F) KOA Speer, [CMF551M0000FKR6](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey71-CMF551M0000FKR6) Vishay / Dale
| R7, R9, R11-R13   | 5   | 220 Ohm, 1%, 0.25W                                                              | [271-220-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-220-RC]) Xicon   | [MF1/4DCT52R2200F](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey660-MF1-4DCT52R2200F) KOA Speer, [CMF55220R00FHEK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey71-CMF55220R00FHEK) Vishay / Dale
| R8oC1             | 1   | 120 Ohm, 1%, 0.25W (or capacitor, see below)                                    | [271-120-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-120-RC]) Xicon   | [MF1/4DCT52R1200F](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey660-MF1-4DCT52R1200F) KOA Speer, [CMF55120R00FKR6](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey71-CMF55120R00FKR6) Vishay / Dale
| R10               | 1   | 3.3 KOhm, 1%, 0.25W                                                             | [271-3.3K-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-3.3K-RC]) Xicon | [MF1/4DCT52R3301F](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey660-MF1-4DCT52R3301F) KOA Speer, [CMF553K3000FKBF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey71-CMF553.3K1%T1) Vishay / Dale
|                   |     |                                                                                 | **Capacitors**
| R8oC1             | 1   | 10 uF (or resistor, see above. C1 best option if using Uno)                     | [ECE-A1HKA100B](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey667-ECE-A1HKA100B) Panasonic | [UST1H100MDD1TE](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey647-UST1H100MDD1TE) Nichicon
|                   |     |                                                                                 | **Switches**
| S1-S2             | 2   | SPDT (See build details for purpose of these switches)                          | [MS12AFG01](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey633-MS12AFG01) NKK
| S1-S2 (Alt)       | 2*  | 1 x 3 header (Could just use wire if will never change)                         | [69190-403](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-69190-403) Amphenol FCI, [929834-02-03-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-03-RK) 3M, [A2-3PA-2.54DSA(71)](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey798-A23PA254DSA71) Hirose | See ALT_HEADER
|                   | 2   | 1 x 2 shorting jumper (Could just use wire if will never change)                | [63429-202LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-63429-202LF) Amphenol FCI | [929951-00](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-951-00) 3M, [M7582-46](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M7582-46) Harwin
|                   |     |                                                                                 | **Multiplexers**
| U1-U6             | 6   | SN74HC4851 (each 1 = 8 ports)                                                   | [microDrum store](http://microdrum.net/blog/products-page-2/basic-components/sn74hc4851/) | [SN74HC4851N](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey595-SN74HC4851N) Texas Instruments
|                   |     |                                                                                 | **Diodes**
| D1                | 1   | 1N4148                                                                          | [1N4148TR](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey78-1N4148) Vishay | [1N4148TR](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey512-1N4148TR) On / Fairchild
|                   |     |                                                                                 | **ICs**
| U7                | 1   | 6N138                                                                           | [6N138](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey782-6N138) Vishay | [6N139M](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey512-6N139M) On / Fairchild
| U8                | 1   | 74LS04 (Midi thru only)                                                         | [SN74LS04N](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey595-SN74LS04N) (Texas Instruments) | 
|                   |     |                                                                                 | **Sockets**
| U1skt-U6skt       | 6   | 16 pin DIP (2x8)                                                                | [DILB16P-223TLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-DILB16P-223TLF) Amphenol FCI | [4816-3004-CP](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-4816-3004-CP) 3M
| U7skt             | 1   | 8 pin DIP (2x4)                                                                 | [DILB8P-223TLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-DILB8P-223TLF) Amphenol FCI   | [4808-3004-CP](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-4808-3004-CP) 3M
| U8skt             | 1   | 14 pin DIP (2x7) (Midi thru only)                                               | [DILB14P-223TLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-DILB14P-223TLF) Amphenol FCI | [4814-3000-CP](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-4814-3000-CP) 3M
|                   |     |                                                                                 | **Connectors**
| CONN1-CONN6       | 6   | 2 x 5 header                                                                    | [67997-410HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-67997-410HLF) Amphenol FCI | [XG8W-1041](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG8W-1041) Omron, [M20-9760546](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9760546) Harwin
|                   | 6   | 2 X 5 socket                                                                    | [65239-005LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65239-005LF) Amphenol FCI   | [XG4M-1030](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG4M-1030) Omron, [M20-1070500](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-1070500) Harwin
| JP1-JP3, JP5, JP6 | 5*  | 1 x 3 header (JP3 - LCD)                                                        | [69190-403](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-69190-403) Amphenol FCI, [929834-02-03-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-03-RK) 3M, [A23PA254DSA71](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey798-A23PA254DSA71) Hirose | See ALT_HEADER
|                   | 5   | 1 x 3 socket (JP3 – LCD)                                                        | [65240-003LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65240-003LF) Amphenol FCI   | [10-11-2034](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-10-11-2034) Molex
| JP4               | 1*  | 1 x 6 header (LCD)                                                              | [68000-406HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-68000-406HLF) Amphenol FCI, [M20-9770646](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9770646) Harwin, [929834-02-06-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-06-RK) 3M | See ALT_HEADER
|                   | 1   | 1 x 6 socket (LCD)                                                              | [65240-006LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65240-006LF) Amphenol FCI   | [M20-1060600](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-1060600) Harwin, [10-11-2063](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-10-11-2063) Molex
| JX                | 1*  | 1 x 2 header (V5 version only - could replace with wire if not going to change) | [929800-01-02](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929800-01-02) 3M, [68000-402](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-68000-402) Amphenol FCI, [M20-9730246](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9730246) Harwin | See ALT_HEADER 
|                   | 1   | 1 x 2 shorting jumper (V5 version only)                                         | [63429-202LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-63429-202LF) Amphenol FCI   | [929951-00](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-951-00) 3M, [M7582-46](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M7582-46) Harwin
| MIDI1-MIDI2       | 2   | 5 pin DIN socket                                                                | [NYS325](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey568-NYS325) REAN / Neutrik| [T3359150](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey523-T3359150) Amphenol FCI
| ARDUINO_CONN      | 2*  | 1 x 8 header                                                                    | [929834-04-08-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-04-08-RK) 3M, [XG8V-0831](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG8V-0831) Omron, [M20-9730846](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9730846) Harwin | See ALT_HEADER 
|                   | 2*  | 1 x 6 header                                                                    | [68000-406HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-68000-406HLF) Amphenol FCI, [M20-9770646](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9770646) Harwin, [929834-02-06-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-06-RK) 3M | See ALT_HEADER
| ALT_HEADER        | 2   | 1 x 32 header - split (will cover all headers with qty marked with \*)          | [929834-02-36-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-36-RK) 3M
| Wire              |     | Ribbon cable, rainbow version optional…                                         | Ebay is best option as Mouser only does long lengths
| Contacts          |     | To fit 22-30 AWG wire (assuming that matches ribbon wire above)                 | [76347-401LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-76347-401LF) Amphenol FCI | [08-50-0114](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-08-50-0114) Molex - Need to make sure compatible with sockets chosen

<br>

There are a number of optional parts in the above list, depending on the build
configuration you require. The following table shows the options outlined on the
Motherboard v0.7 board:

| Part | V5 - Thru | V3.3 - Thru | V5 - No Thru | V3.3 - No Thru | 
| ---- | --------- | ----------- | ------------ | -------------- |
| S2   | Left      | Right       | Left         | Right          |
| JX   | Close     | Open        | Close        | Open           |
| R11  | Yes       | Yes         | No           | No             |
| R12  | Yes       | Yes         | No           | No             |
| R13  | No        | Yes         | No           | Yes            |
| U8   | Yes       | Yes         | No           | Yes            |

<br>

**NB**: S1 is used to determine if the Arduino resets automatically when it is
connected to the computer via USB.
If you do not wish it to reset every time you connect it set this to closed.

## Jack Board v0.4

| Part     | Qty | Description                                                      | Manufacturer Part No
| -------- | --- | ---------------------------------------------------------------- | --------------------
|          |     |                                                                  | **Circuit Board**
| PCB      | 1   | Jack Board v0.4                                                  | [DIY](/downloads/microDRUM_Jack_v0.4-PCB.pdf)
|          |     |                                                                  | **Jacks**
| U1-U4    | 4   | Mono sockets for single piezo trigger, stereo for two            | Stereo: [NMJ6HFD2](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey550-20301), [NRJ6HF-1](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey550-20384) or Mono: [NMJ4HHD2](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey568-NMJ4HHD2) Neutrik
|          |     |                                                                  | **Resistors**
| R1-R4    | 4   | 1 MOhm or 100 Ohm with HHC Resistor; 1%, 0.25W                   | Xicon 271 range
|          |     |                                                                  | **Switches**
| S1-S4    | 1   | 1 x 12 header                                                    | [929834-02-12-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-12-RK) 3M
| Jumper   | 4   | 1 x 2 shorting jumper (Could just use wire if will never change) | [63429-202LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-63429-202LF) Amphenol FCI, [929951-00](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-951-00) 3M or [M7582-46](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M7582-46) Harwin
|          |     |                                                                  | **Connectors**
| Conn1    | 1   | 2 x 5 header                                                     | [67997-410HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-67997-410HLF) Amphenol FCI, [XG8W-1041](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG8W-1041) Omron or [M20-9760546](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9760546) Harwin
|          | 1   | 2 x 5 socket                                                     | [65239-005LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65239-005LF) Amphenol FCI, [XG4M-1030](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey653-XG4M-1030) Omron or [M20-1070500](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-1070500) Harwin
| Contacts |     | To fit 22-30 AWG wire (assuming that matches ribbon wire above)  | [76347-401LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-76347-401LF) Amphenol FCI or [08-50-0114](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-08-50-0114) Molex - Need to make sure compatible with sockets chosen
| Wire     |     | Ribbon cable, rainbow version optional…                          | Ebay is best option as Mouser only does long lengths

<br>

**NB**: These quantities are for a single board, giving you 4 sockets.

## LCD v0.1

There is currently no PCB available for this module, use stripboard or perfboard
to build this.

| Part       | Qty | Description                                                           | Mouser Part No           | Alternatives
| ---------- | --- | --------------------------------------------------------------------- | ------------------------ | ------------
|            |     |                                                                       | **Circuit Board**
| PCB        | 1   | Stripboard                                                            | [ST2](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey854-ST2) BPS
|            |     |                                                                       | **Resistors**
| R1         |     | 10 KOhm variable resistor                                             | [T93XA103KT20](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey72-T93XA-10K) Vishay
| R2-R4      | 3   | 10 KOhm, 1%, 0.25W                                                    | [271-10K-RC](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey271-10K-RC) Xicon | [MF1/4DCT52R1002F](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey660-MF1-4DCT52R1002F) KOA Speer, [CMF5510K000FKEK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey71-CMF5510K000FKEK) Vishay
|            |     |                                                                       | **Switches**
| S1-S3      | 3   | SPST, Momentary                                                       | [1301.9302](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey693-1301.9302) Schurter
|            |     |                                                                       | **Screen**
|            | 1   | 16 x 2 screen                                                         | [NMTC-S16205DRGHS](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkeyNMTC-S16205DRGHS) Microtips Technology | EBay is a good source, with a wide range of colours available
|            |     |                                                                       | **Connectors**
| JP3        | 1*  | 1 x 3 header                                                          | [69190-403](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-69190-403) Amphenol FCI, [929834-02-03-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-03-RK) 3M, [A2-3PA-2.54DSA(71)](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey798-A23PA254DSA71) Hirose | See ALT_HEADER
|            | 1   | 1 x 3 socket                                                          | [65240-003LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65240-003LF) Amphenol FCI   | [10-11-2034](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-10-11-2034) Molex
| JP4        | 1*  | 1 x 6 header                                                          | [68000-406HLF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-68000-406HLF) Amphenol FCI, [M20-9770646](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-9770646) Harwin, [929834-02-06-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-06-RK) 3M | See ALT_HEADER
|            | 1   | 1 x 6 socket                                                          | [65240-006LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-65240-006LF) Amphenol FCI   | [M20-1060600](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey855-M20-1060600) Harwin, [10-11-2063](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-10-11-2063) Molex
| ALT_HEADER | 1   | 1 x 32 header - split (will cover all headers with qty marked with \*) | [929834-02-36-RK](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey517-929834-02-36-RK) 3M
| Contacts   |     | To fit 22-30 AWG wire                                                 | [76347-401LF](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey649-76347-401LF) Amphenol FCI | [08-50-0114](https://eu.mouser.com/Search/ProductDetail.aspx?R=0virtualkey0virtualkey538-08-50-0114) Molex - Need to make sure compatible with sockets chosen
