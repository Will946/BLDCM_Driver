# BLDCM KiCad Library

Welcome to my personal collection of KiCad library files. This repository is designed for my own use but is publicly available. It includes custom schematic symbols, PCB footprints, and associated 3D models.

---

## 📚 Library Contents

This library (`BLDCM`) contains the following components:

### Schematic Symbols

Here are the custom symbols available in the `BLDCM.kicad_sym` library.

| Symbol | Description | Default Footprint |
| :--- | :--- | :--- |
| **AS5048A** | Magnetic Rotary Encoder 14-Bit | `BLDCM:TSSOP-14` |
| **BAT54S** | SMD Small Signal Schottky Diodes | `BLDCM:SOT-23` |
| **C** | Unpolarized capacitor | `BLDCM:C_0402` |
| **D_Schottky** | Schottky Diode | - |
| **D_Schottky_B0520LW** | Schottky Diode | `BLDCM:SOD-123` |
| **ECS-3225MVLC-240-CN** | Crystal Oscillator 24MHz ±25ppm | `BLDCM:Crystal_3225` |
| **ESDA25W** | ESD suppressors / TVS diodes 25V 400W Unidirect | `BLDCM:SOT-323` |
| **GND** | Ground power symbol | - |
| **INA239-Q1** | High-Precision Power Monitor With SPI Interface | `BLDCM:VSSOP-10` |
| **INA240AXPW** | Ultra-Precise Current Sense Amplifier | `BLDCM:TSSOP-8` |
| **ISM330DHCX** | iNEMO Inertial Measurement Unit (IMU) | `BLDCM:LGA-14L` |
| **JLINK_14P_FTSH-107-01-L-DV-K-TR** | J-Link 14-Pin STMicroelectronics standard | `BLDCM:FTSH-107-01-L-DV-K-TR` |
| **LDL212PV33R** | LDO Voltage Regulator 1.2A 3.3V | `BLDCM:DFN-6-2x2` |
| **LDLN030G33R** | LDO Voltage Regulator 300mA 3.3V Ultra-Low Noise | `BLDCM:TSOT-23-5` |
| **LDO40LPU50RY** | LDO Voltage Regulator 400mA 5V | `BLDCM:DFN-6-3x3` |
| **LED_SK6805-EC15** | Addressable RGB LED 1.5x1.5mm | `BLDCM:LED-1515` |
| **MT6701** | Hall-Based Angle Position Encoder Sensor | `BLDCM:SOP-8` |
| **Molex_05MM-30P** | Molex SlimStack Connector 0.5mm 30-pin | `BLDCM:501920-3001` |
| **Molex_05MM-30P-F** | Molex SlimStack Receptor 0.5mm 30-pin | `BLDCM:52991-0308` |
| **Molex_125MM-3P-H** | Molex PicoBlade Connector 1.25mm 3-pin RA | `BLDCM:53048-0310` |
| **Molex_125MM-4P-H-SMD** | Molex PicoBlade Connector 1.25mm 4-pin RA SMD | `BLDCM:53261-0471` |
| **Molex_MicroLock_2MM-2R-4P-H-SMD** | Molex Micro-Lock Plus Header 2.0mm 4-pin Dual Row RA | `BLDCM:220205-0471` |
| **Molex_MicroLock_2MM-4P-H-SMD** | Molex Micro-Lock Plus Header 2.0mm 4-pin Single Row RA | `BLDCM:505578-0460` |
| **R** | Resistor | `BLDCM:R_0402` |
| **R_KRL1220** | Current Sense Resistor SMD 0.3W 50mOhm 1% | `BLDCM:KRL1220` |
| **SN74LV1T34** | Single Buffer GATE CMOS Logic Level Shifter | `BLDCM:SOT-23-5` |
| **STM32F446RE** | STM32F446RE Microcontroller | `BLDCM:LQFP64` |
| **Switch_EVP-AKE31A** | Side-operational SMD Light Touch Switch | `BLDCM:EVPAKE31A` |
| **TCAN1462** | CAN FD Transceiver | `BLDCM:VSON-8` |
| **TMC6300-LA** | Motor Driver for 3-Phase BLDC/PMSM | `BLDCM:QFN-20` |
| **TP** | Test Point | `BLDCM:TP_0.5mm` |
| **TPS2115ADRB** | Two-Input, One-Output Power Multiplexer | `BLDCM:VSON-8` |
| **TPS2121** | 2.8V to 22V Priority Power MUX | `BLDCM:VQFN-HR-12` |
| **USB_12402012E212A** | Amphenol USB 2.0 Type C Connector | `BLDCM:12402012E212A` |
| **USB_217179-0001** | Molex USB 2.0 Type C Connector | `BLDCM:217179-0001` |
| **VDD** | Source power symbol | - |

<br>

### PCB Footprints & 3D Models

The following footprints are available in the `BLDCM.pretty` library. Almost all footprints have a corresponding 3D model in the `BLDCM.3dshapes` directory.

| Footprint | Description | Has 3D Model? |
| :--- | :--- | :---: |
| **12402012E212A** | Amphenol USB Type-C Connector, 16-pin | ✅ |
| **217179-0001** | Molex USB Type-C Connector, 16-pin | ✅ |
| **220205-0471** | Molex Micro-Lock Plus Header, 2mm, 4-pin, Dual Row, RA | ✅ |
| **501920-3001** | Molex SlimStack Board-to-Board Connector, 0.5mm, 30-pin | ✅ |
| **505578-0460** | Molex Micro-Lock Plus Header, 2mm, 4-pin, Single Row, RA | ✅ |
| **52991-0308** | Molex SlimStack Board-to-Board Receptor, 0.5mm, 30-pin | ✅ |
| **53048-0310** | Molex PicoBlade Header, 1.25mm, 3-pin, RA | ✅ |
| **53261-0471** | Molex PicoBlade Header, 1.25mm, 4-pin, RA, SMD | ✅ |
| **C_0201, C_0402, C_0603, C_0805** | SMD Capacitor Packages | ✅ |
| **Crystal_3225** | SMD Crystal, 3.2x2.5 mm | ✅ |
| **DFN-6-2x2, DFN-6-3x3** | Dual Flat No-Lead Packages, 6-pin | ✅ |
| **EVPAKE31A** | Panasonic Side-operational Tactile Switch | ✅ |
| **FTSH-107-01-L-DV-K-TR** | Samtec FTSH Header, 1.27mm, 14-pin | ✅ |
| **KRL1220** | ROHM Current Sense Resistor, 1220 package | ✅ |
| **LED-1515** | SMD LED, 1.5x1.5 mm | ✅ |
| **LGA-14L** | Land Grid Array Package, 14-pin | ✅ |
| **LQFP64** | Low-profile Quad Flat Package, 64-pin | ✅ |
| **QFN-20** | Quad Flat No-Lead Package, 20-pin | ✅ |
| **R_0201, R_0402, R_0603, R_0805, R_1210** | SMD Resistor Packages | ✅ |
| **SOD-123** | Small Outline Diode Package | ✅ |
| **SOP-8** | Small Outline Package, 8-pin | ✅ |
| **SOT-23, SOT-23-5, SOT-323** | Small Outline Transistor Packages | ✅ |
| **TP_0.5mm, TP_1.0mm, TP_2.0mm** | Circular Test Point Pads | ❌ |
| **TSOT-23-5** | Thin Small Outline Transistor Package, 5-pin | ✅ |
| **TSSOP-8, TSSOP-14** | Thin-Shrink Small Outline Packages | ✅ |
| **VQFN-HR-12** | Very-thin Quad Flat No-Lead Package, 12-pin | ✅ |
| **VSON-8** | Very-thin Small Outline No-Lead Package, 8-pin | ✅ |
| **VSSOP-10** | Very-thin-Shrink Small Outline Package, 10-pin | ✅ |

---

## 🚀 Getting Started (Adding to KiCad)

To use this library in your KiCad projects, follow these steps:

1.  **Clone or Download:** Get a local copy of this repository.

2.  **Configure KiCad Paths:**
    * Open KiCad and go to `Preferences` -> `Configure Paths...`.
    * Click the `+` icon to add a new path.
    * Set the **Name** to `BLDCM_DIR` and the **Path** to the location where you cloned the repository.

3.  **Add Symbol Library:**
    * Go to `Preferences` -> `Manage Symbol Libraries...`.
    * Select the 'Global Libraries' or 'Project Specific Libraries' tab.
    * Click the folder icon to "Add existing library" and select the `BLDCM.kicad_sym` file from the repository folder.

4.  **Add Footprint Library:**
    * Go to `Preferences` -> `Manage Footprint Libraries...`.
    * Select the 'Global Libraries' or 'Project Specific Libraries' tab.
    * Click the folder icon and select the `BLDCM.pretty` directory from the repository folder.

The new symbols and footprints will now be available in the KiCad editors!
