# Node-RED Flow - Weather for Awtrix device

## Description
A Node-RED flow that retrieves the temperature from a specified city and sends the data to an Awtrix device.<br />
The data is updated every 10 minutes.<br />
Icons are set according to the weather condition.

## Pre-import instructions
Before importing the flow into Node-RED, make sure to edit the following three values:

1. `<city>` - The name of the city for which you want to retrieve the temperature.
2. `<api_key>` - Your API key for the weather service ([https://openweathermap.org](https://openweathermap.org/api)).
3. `<awtrix_ip>` - The IP address of your Awtrix device.
