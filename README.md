# GardenControl

> The GardenControl is an intelligent watering system to control sprinklers, pumps and sensors. 

+ 12x outputs for valve control (24VAC)
+ 2x outputs for external 230V relais (e.g. for 230V pumps)
+ 2x 4-20mA inputs (for e.g. water level sensors and  each output can provide driectly the 24VDC PWR for the sensor, no additional Power supply necessary)
+ 4x ADC inputs 0-12V (e.g. for Humidity, pressure, temperature, ..., -sensors)
+ 3x Binär-inputs (e.g. for switches, S0-Interface, Rainssensor, ...)

## Connection Diagram

### 24V AC Connection

The GardenControl need a 24VAC Transformer. This Transfomer provide the power for the valves/relays and for all other funktions. No additional PWR-Supply necessary.

NOTE: you have to protect the system always with an external 3A FUSE. In case the transformer has a integrated Fuse (<=3A) it is also fine.  

![AnschlussPWR](doc/picture/AnschlussPWR.PNG)

### Valves Connections

You can connect up to 12 valves.

NOTE: ensure that the total current consumption of all parallel open valves is always < 3A

![AnschlussVentile](doc/picture/AnschlussVentile.PNG)

### Relay Connections
![AnschlussRelais](doc/picture/AnschlussRelais.PNG)

### 4-20mA Inputs
![Anschluss4-20mA](doc/picture/Anschluss4-20mA.PNG)

### Binary-Inputs
![AnschlussBIN](doc/picture/AnschlussBIN.PNG)

### ADC-Inputs
![AnschlussADC](doc/picture/AnschlussADC.PNG)

### So-Inputs (not in all Firmware types available) 
![AnschlussS0](doc/picture/AnschlussS0.PNG)

## Firmware 

Firmware | Description | Link
-------- | -------- | --------
ESPHome  | Inhalt   | [link ESPhome Yaml](ESPHome_Firmware/esp32-gardencontrol.yaml)
Tasmota   | Inhalt   | [link Tasmota_Firmware](https://gitlab.com/noschFRQ/esp32-gardencontrol)

## Hardware Block-Diagram
![Block-Diagramm](doc/picture/GardenControl_Block_Diagram.png)

## Hardware PCB Overview
![PCB_TOP](doc/picture/GardenControl_PCB_TOP.png)
![PCB_BOT](doc/picture/GardenControl_PCB_BOT.png)
