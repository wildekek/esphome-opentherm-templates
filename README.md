# esphome-opentherm
Template(s) to use Opentherm boilers in ESPHome

Get full control over your boiler/heating system trough ESPHome and Home Assistant.
- This replaces expensive Tado/Nest thermostats for only $20-$25 in hardware costs.
- Save energy with full control over boiler temperature/thermostat PID loops.


Hardware requirements:
- HVAC system that supports OpenTherm
- WeMos/LOLIN D1 mini or WeMos D1 MINI ESP32
- [DIYless Opentherm Master Shield](https://diyless.com/product/master-opentherm-shield)
- Thermometer that is supported by Home Assistant and frequently updates. I recommend the Xiaomi Mijia (LYWSD03MMC) using [this firmware](https://github.com/pvvx/ATC_MiThermometer).


Software requirements:
- Home Assistant
- ESPHome add-on

Supported HVAC Systems
- [Remeha Avanta](https://github.com/wildekek/esphome-opentherm/blob/main/remeha-avanta.yaml)
(The above example can be easily adapted to other systems)

# Example device in Home Assistant

<img width="525" alt="image" src="https://user-images.githubusercontent.com/2332647/206486063-3892970f-e4e0-4d5e-bfc2-dd6db29e2635.png">
