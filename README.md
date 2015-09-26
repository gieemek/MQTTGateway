MyMQTT Broker Gateway for RFM69
===============================

This Arduino sketch is based on MySensors MQTTGateway example (MySensors library v.1.5) by Daniel Wiegert.

MySensors library v.1.5 is prepare to work with NRF24L01+ or RFM69 radio module, but software SPI is not implemented for RFM69. So you can't use RFM69 if you want to build Ethernet or MQTT Gateway (Ethernet Shield or W5100 module uses SPI pins too).

I modified the original version of MQTTGateway.ino sketch, and now I can use it with RFM69 module via software SPI and ethernet shield via hardware SPI. Download of RFM69_softSPI library and modify of MyConfig.h file are necessary - you can find them in another my repositories.

