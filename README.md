# espcb-bms-comms
An ESP32 series based PCB facilitating BMS comms to Solar Inverters

# Features
1. Choice of CAN/~~RS485~~ for Inverter Communication
2. When using CAN, the choice is SN65HVD230 ~~or TJA1050/1051T~~
3. Three PCB variants based on: ESP32 DevKit, Seeed Studio XIAO S3, ~~or the S3-WROOM-1 module~~
4. Can be powered either by USB-C, ~~AC power supply, or LV Battery itself (mutually exclusive)~~
5. BMS connection through either UART, BLE ~~,CAN or RS485~~
6. Provision for 120Ohm Termination resistor jumper select
   
# References/Sources/Insights

0. https://github.com/Sleeper85/esphome-jk-bms-can
1. https://kicad-downloads.s3.cern.ch/index.html?prefix=windows/nightly/
2. https://github.com/syssi/esphome-jk-bms
