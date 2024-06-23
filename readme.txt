This is an ASCOM Alpaca switch driver. This driver controls 3 WiFi smart switches that run Tasmota software.
https://tasmota.github.io/docs/
The switches are controlled directly and do not use a MQTT broker.
The driver was developed using the AlpycaDevice SDK 0.5.0 
https://github.com/ASCOMInitiative/AlpycaDevice
It is functional and passes ConformU. There a a few additions to make before I call it finished.
The IP address and names for the switches are stored in the config.toml file. Change these to meet your needs.