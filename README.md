# GardenControl

> The GardenControl is an intelligent watering system to control sprinklers, pumps and sensors. 

+ 12x outputs for valve control (24VAC)
+ 2x outputs for external 230V relais (e.g. for 230V pumps)
+ 2x 4-20mA inputs (for e.g. water level sensors and  each output can provide driectly the 24VDC PWR for the sensor, no additional Power supply necessary)
+ 4x ADC inputs 0-12V (e.g. for Humidity, pressure, temperature, ..., -sensors)
+ 3x Binär-inputs (e.g. for switches, S0-Interface, Rainssensor, ...)

## Connection Diagram

### 24V AC Connection
![AnschlussPWR](doc/picture/AnschlussPWR.PNG)

### Valves Connections
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
ESPHome  | Inhalt   | [link ESPhome Yaml](esp32-gardencontrol.yaml)
Tasmota   | Inhalt   | Inhalt

## Hardware Block-Diagram
![Block-Diagramm](doc/picture/GardenControl_Block_Diagram.png)


