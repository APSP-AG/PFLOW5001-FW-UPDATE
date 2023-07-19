# Repository Contents

This repository contains:

- Angst+Pfister Test Studio software
- Latest firmware file (.bin file)
- Manual for Angst+Pfister Test Studio software
- Manuals for both USB adapters (EX-1309-T and MIKROE-1203)
- Datasheet for PFLOW5001 flow sensor

# PFLOW(C)5001 Firmware Update Guide

This guide covers the initial setup for a firmware update for PFLOW5001/PFLOWC5001 flow sensors using the Angst+Pfister Test Studio software. The actual firmware update process is detailed in the separate manual.


## Table of Contents

- [Preparation](#1-preparation)
- [Connect the Sensor](#2-connect-the-sensor)
  - [RS232 TTL Connection](#21-rs232-ttl-connection)
  - [RS232 EIA Connection](#22-rs232-eia-connection)
  - [RS485-2W Connection](#23-rs485-2w-connection)
- [Launch the Software](#3-launch-the-software)
- [Support](#support)

## 1. Preparation

  Before starting the process, you need to download the necessary files from the repository.
  
  ### 1.1 Download Files from GitHub
  
  - Click on the green `Code` button. It is usually located near the top right of the page.
  - In the dropdown, click `Download ZIP`.
  - Once the ZIP file is downloaded, extract it. You should now have access to the Angst+Pfister Test Studio software, firmware file, manuals for the software, firmware upgrade process, and USB adapters, as well as the datasheet for PFLOW5001 sensor.
  
  ### 1.2 Determine appropriate USB adapter
  - Ensure you have the appropriate USB adapter at hand. Use EX-1309-T for RS485 and RS232 EIA, or MIKROE-1203 for RS232 TTL.

## 2. Connect the Sensor

- Connect the VCC and GND of the sensor with a 8-24V power supply. The correct pins are labeled on the provided wires or can be found in the sensor datasheet.
- Connect your flow sensor to the USB adapter. (see procedure for different protocols below)
- Connect the USB adapter to your PC.
- Power on your PFLOW5001/PFLOWC5001 sensor.

  
### 2.1 RS232 TTL connection:
- Use the MIKROE-1203 adapter: <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/3e8f41c8-4f73-4c66-b20c-58a7fb532e3f)
- Wire the flow sensor's TX (Transmit) to the adapter's RX (Receive)
- Wire the sensor's RX (Receive) to the adapter's TX (Transmit)
- Connect the GND pins of the sensor, adapter and power supply.

### 2.2 RS232 EIA connection:
- Use the EX-1309-T adapter: <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/1eaa6cca-9ca9-4115-b171-801c4f335ed0)
- Set the adapter's dip switches to the following combination: <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/3321004a-2868-4c47-a407-1b295f0feb9b)
- Wire the flow sensor's TX (Transmit) to the adapter's RX (Receive)
- Wire the sensor's RX (Receive) to the adapter's TX (Transmit)
- Connect the GND pins of the sensor, adapter and power supply. <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/7345bf0f-7717-4e94-b3cc-053a07572c0a)


### 2.3 RS485-2W connection:
- Use the EX-1309-T adapter: <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/1eaa6cca-9ca9-4115-b171-801c4f335ed0)
- Set the adapter's dip switches to the following combination: <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/314ec5f0-b7cb-4400-b4d5-6402325132bd)
- Wire the flow sensor's D+ (Data Positive) to the adapter's D+
- Wire the sensor's D- (Data Negative) to the adapter's D-
- Connect the GND pins of the sensor, adapter and power supply. <br/> ![image](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/assets/72441261/86278c84-6b89-4744-9c1f-27794d3b4c0b)


## 3. Launch the Software

- Open Angst+Pfister Test Studio software on your PC.
- Please refer to the detailed instructions on how to update the firmware in the separate manual.

## Support

If you have any issues or questions regarding the firmware update process, please post in the [discussions](https://github.com/APSP-AG/PFLOW5001-FW-UPDATE/discussions) section of this repository or contact michel.krapf@angst-pfister.com directly. Our team will be glad to assist you.
