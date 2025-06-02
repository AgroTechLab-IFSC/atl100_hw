![GitHub Release](https://img.shields.io/github/v/release/agrotechlab-ifsc/atl100_hw)
![GitHub Platform](https://img.shields.io/badge/Platform-KiCad-blue)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/agrotechlab-ifsc/atl100_hw)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/agrotechlab-ifsc/atl100_hw)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues-pr/agrotechlab-ifsc/atl100_hw)
![GitHub followers](https://img.shields.io/github/followers/agrotechlab-ifsc)
![GitHub forks](https://img.shields.io/github/forks/agrotechlab-ifsc/atl100_hw)
![GitHub Repo stars](https://img.shields.io/github/stars/agrotechlab-ifsc/atl100_hw)
![GitHub watchers](https://img.shields.io/github/watchers/agrotechlab-ifsc/atl100_hw)
![GitHub License](https://img.shields.io/github/license/agrotechlab-ifsc/atl100_hw)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/agrotechlab-ifsc/atl100_hw/total)

# ATL-100 (Hardware)

**ATL-100** is a multiparametric station developed by <a href="https://agrotechlab.lages.ifsc.edu.br">AgroTechLab (*Agribusiness Technology Development Laboratory*)</a> of <a href="https://www.ifsc.edu.br">IFSC (*Federal Institute of Santa Catarina*)</a>.

It can be used as meteorological station, agrometeorological station, hydrological station, aquaculture station, tide gauge station or fire monitoring station (forest or urban environment).

It is a PTH (*Plated-Through-Hole*) project based on the ESP32-S3 MCU that aims to be easy to produce and low cost, so it uses COTS (*Commercial Off-The-Shelf*) hardware.

## Features

The current version of the ATL-100 has the following features:

### Main Board

 - Power Supply (XL4005)
   - Input: 10V ~ 30V;
   - Current: 2.5A (typ.) / 5A (max. with heat sink);
   - Efficiency: 90%
   - Frequency: 300KHz
 - Power Supply Sensor
   - Voltage Divider (30V -> 3.33V);
 - MCU (ESP32-S3)
   - RISC 32 bits 240MHz dual-core;
   - 16Mb Flash;
   - 512Kb SRAM;
   - 16Kb SRAM in RTC;
   - 8Mb PSRAM;
   - 384Kb ROM;
 - RS-485 (HW-519)
   - TTL to RS-485 converter;
   - Modbus-RTU protocol;
   - Used to connect HaliSense TH-EC-PH-NPK soil sensor:
     - Soil temperature (-40 ~ 80 ℃);
     - Soil moisture (0 ~ 100 %);
     - Soil electroconductivity (0 ~ 20.000 us/cm);
     - Soil pH (3 ~ 9 pH);
     - Soil nitrogen, phosphorus, potassium (1 ~ 1999 mg/Kg or mg/L)
 - Windsock (voltage drop based);
 - Anemometer (pulse counter based);
 - Pluviometer (pulse counter based);
 - Air sensor (BME-280)
   - Air Temperature (-40 ~ 85 ℃);
   - Air Humidity (0 ~ 100 %);
   - Atmospheric Pressure (300 ~ 1100 hPa);

### ADC Board
 - ADC (ADS1115)
   - 16 bits resolution;
   - 4 channels (4mA ~ 20mA / 0V ~ 10V);

## 3D Images
![Image 1](./atl100_board_1.png "3D image 1")
![Image 2](./atl100_board_2.png "3D image 2")
![Image 3](./atl100_board_3.png "3D image 3")

<br><hr><p style="text-align: center;">All rights reserved. &copy; Since 2020.<br><b><a href="https://agrotechlab.lages.ifsc.edu.br/">AgroTechLab (<i>Agribusiness Technology Development Laboratory</i>)</a></b><br>
<b><a href="https://ifsc.edu.br/web/campus-lages">IFSC (<i>Federal Institute of Santa Catarina</i>) - Campus Lages</a></b><br>
225 Heitor Vila Lobos St., São Francisco<br>
Lages/SC - Brazil<br>
88506-400</p>