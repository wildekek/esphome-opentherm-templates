# What are esphome-opentherm-templates?
These are drop-in files for ESPHome to make it easy to start controlling your OpenTherm HVAC system from Home Assistant.

<img width="567" alt="image" src="https://user-images.githubusercontent.com/2332647/206578733-fa3b681d-85eb-4e27-8c7b-7f35017d429e.png">


## Why should I want this?
- This replaces expensive Tado/Nest thermostats for only $20-$25 in hardware costs. No proprietary clouds and vendors!
- You get full control over your HVAC system in Home Assistant with ESPHome. All the settings, all the graphs.
- Save energy with full control over your HVAC system. Tweak temperatures, create power saving modes.

## Credits
This repo was inspired by the work of @arthurrump who created the [esphome-opentherm](https://github.com/arthurrump/esphome-opentherm) project.

## Hardware requirements:
- HVAC system that supports [OpenTherm](https://en.wikipedia.org/wiki/OpenTherm)
- [WeMos/LOLIN D1 mini](https://www.wemos.cc/en/latest/d1/d1_mini.html) or [WeMos S2 MINI](https://www.wemos.cc/en/latest/s2/s2_mini.html)
- [DIYless Opentherm Master Shield](https://diyless.com/product/master-opentherm-shield)
- Thermometer that is supported by Home Assistant.
  - At least 1 decimal accuracy
  - High update frequency (<1 min)
  - I recommend the [Xiaomi Mijia](https://aliexpress.com/wholesale?SearchText=LYWSD03MMC) using [this firmware](https://github.com/pvvx/ATC_MiThermometer).


## Software requirements:
- [Home Assistant](https://www.home-assistant.io/)
- [ESPHome add-on](https://esphome.io/guides/getting_started_hassio.html)

## Supported HVAC Systems
- [Remeha Avanta](https://github.com/wildekek/esphome-opentherm/blob/main/remeha-avanta.yaml)
(The above example can be easily adapted to other systems)

## Example device in Home Assistant
<img width="525" alt="image" src="https://user-images.githubusercontent.com/2332647/206486063-3892970f-e4e0-4d5e-bfc2-dd6db29e2635.png">
