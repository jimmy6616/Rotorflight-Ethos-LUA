# RFSuite LUA Suite Guide operating with Rotorflight Configurator

## Introduction
You can adjust a variety of settings using only your transmitter with the Rotorflight Lua scripts. They allow you to change things like PIDs, rates, filters, failsafe and governed headspeed at the field. 

Pre-requisites:

- Ethos 1.5 or newer on the transmitter and

- an FrSky SmartPort or F.Port receiver.

- or a CRSF v2.11 or newer receiver.

- or an ELRS 2.0.1 or newer receiver.


**NOTE: Ff you have a radio with both eMMC and an SDCARD such as a X20Pro\RS you MUST install onto the SDCard**

Examples:

- Frsky Tandem X20S with an Archer receiver and F.port protocols.
- Frsky Ethos Radio (X18, X14 etc) with either SPORT,FPORT receiver or ELRS with an external module.


If you're using F.Port, start up the Rotorflight Configurator, go to the Configuration tab and enable the TELEMETRY feature. F.Port telemetry does not work without enabling this feature.

If telemetry is working properly on your system, the Lua scripts should also work.

# Ethos Installation
Download the Ethos LUA Suite for Frsky [latest release](https://github.com/rotorflight/rotorflight-configurator/releases) and save the zip file to your PC\laptop

Open Frsky Ethos Suite and connect the USB-C cable, once connected, select Lua Development tools, 

![image](https://github.com/jimmy6616/Rotorflight-Ethos-LUA/blob/img/Ethos_lua_1.jpg)

Select, Install LUA Scripts and choose the zip file from the download above, select rfsuite and Install LUA Sctipts



![image](https://github.com/jimmy6616/Rotorflight-Ethos-LUA/blob/img/Ethos_lua_2.jpg)

Close Ethos Suite

Disconnect the transmitter and power off\on. Once powered on press SYS key and scroll to the end page, the following should be shown.


![image](https://github.com/jimmy6616/Rotorflight-Ethos-LUA/blob/img/sys_rf.jpg)

## IMPORTANT: Changes will only be written to the eeprom when the aircraft is moved from Armed to Diasarmed, if you disconnect power when in an Armed state the changes will not be saved to eeprom.

**If installing for ELRS please see the [seperate section] (https://github.com/jimmy6616/Rotorflight-Ethos-LUA/blob/main/README.md#elrs-installation) at the bottom of this guide**

Ensure the aircraft receiver and FBL are powered, Select the ICON above and you should see the following:

![image](https://github.com/jimmy6616/Rotorflight-Ethos-LUA/blob/img/Ethos_lua_3.jpg)

In the example below of the PID's screen:

PID's #1  - Will change depending on which profile you have your transmitter profile\bank switch set i.e. PID's #2, PID's #3 etc

MENU - Will take you to the top level menu (Please ensure you have clicked SAVE before exiting)

SAVE - Will write your changes to eeprom

? - Is the help screen with useful information

![image](https://github.com/jimmy6616/Rotorflight-Ethos-LUA/blob/img/pid_help1.jpg)

# ELRS Installation

# ELRS Installation
Download the latest ELRS zip file [latest release](https://github.com/FrSkyRC/ETHOS-Feedback-Community/blob/1.5/lua/modules/elrs/elrs.zip) and save the zip file to your PC\laptop











