### Due to large no. of files, content here includes only changed files in their respective ESPEasy-directories.

### This is V2-version with "optimized" tvoc-calculation. In comparison  to V1-calculation version, seems to be that the responsivity to changes
Seems to be much more intensive to V1 also the cutdown when values enter baseline is also happening. The V2 seems not to be as reliable as V1-calculation.

Comparison between V1 / V2 / MH-Z19B (real CO2) readings: 
<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/V1_V2_MHZ19.png" width="900"> 

Responses and overshooting of V2 to fast TVOC change: 
<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/V2_Sprungantwort.png" width="900"> 

## Documentation & more info:

Actually, this TVOC calculation is as Version 2 under development. Seems V2 have also some mirroring effects in comparison to BSEC-algrithm and V1.

<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/V2_gespiegelt.png" heigt=300/>

Project documentation could be found at FHEM-Forum (german): [here](https://forum.fhem.de/index.php?topic=119678.msg1141237#msg1141237)

## For [FHEM](https://forum.fhem.de/)

Slink-device will be auto-detected and created, some additional files are needed for this functionality. Copy them to FHEM-directory:

Grab them at:  https://github.com/herrmannj/AirQuality/tree/master/FHEM

## Sources: 

ESPEasy (@March, 2021): https://github.com/letscontrolit/ESPEasy

## Version: 

ESPEasy-mega-20210223: https://github.com/letscontrolit/ESPEasy/releases/tag/mega-20210223

Every BME680--Module (ADR: 0x76 + 0x77, configurable) is supported. Care about positioning, because of temperature-offset may be caused by ESP8266.

Any contribution is apreciated and welcome!

## Basic schematic:

<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/BME680_Wemos_D1_OSHPARK_Modul.jpg" width="900">

###Konfiguration:

<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/Running_ESP_Easy.png" width="900" >

###I2C-Setting:

<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/ESP_Easy_I2C_Interface_Einstellungen.png" width="900" >

###My BME680-DIY-Module (set ADDR-Pin to GND for 0x76 I2C-address:

<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/OSH%20Park%20%7E%20Shared%20Projects%20by%20MightyPork.png" width="900" >


<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/ESP_Easy_BME680-TVOC_edit.png" width="900" >


<img src="https://github.com/juergs/ESPEasy-mega_BME680_TVOC_20210223/blob/main/ESP_Easy_BME680_Device.png" width="900" >
