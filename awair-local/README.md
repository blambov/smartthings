# AWAIR local API driver

Smartthings Edge driver for AWAIR devices using their local API.

To add devices, use the Smartthings app's "Add device" and "Scan nearby". It should find all AWAIR devices on the local 
network and create a mapping for each of them.

Air quality, temperature, humidity, CO2, VOC, and PM2.5 value are reported. Note: the air quality value is inverted
(i.e. 0 is optimal, 100 is worst) to agree with Smartthings' expectations for the scale.


