# Mi-zoo
Complete list of Xiaomi Mi Smart Home Ecosystem devices with descriptions and codes

### Pages:
- **[Devices (en)](https://lucidyan.github.io/mi-zoo/markdown/devices.html)** - markdown page with all devices with image, model id, product number
___
### What is this repository for?
It was created because Xiaomi has a very confusing lineup with many undocumented differences. 
There is no single source of information about the relationship between **Model ID -> Model / Product Number**. 
I hope this repository will help developers not get confused in this zoo of devices.

___
### Description structure example
[Source](https://www.gizmocentral.com/products/xiaomi-mi-smart-standing-fan-pro)
- **Brand**: Xiaomi
- **Model**: My Smart Standing Fan Pro (ZLBPSP01XY)
- **Product Number**: PYV4009GL - current software modification of original model
- **Model ID**: dmaker.fan.p15 - internal model code that used for interaction with other devices like gateways and for miio/miot protocol communication.

___
### Useful links:
- [(Ru) MiHome Ecosystem GoogleSheet](https://docs.google.com/spreadsheets/d/1quCLYmbA2dku2-M-SNfLEMv8xsgZsSZeGy2zWAEWVVM/edit#gid=2134066630) - Best resource. GoogleSheet with descriptions, integrations, shop and other links.
- [(En/Es) Xiaomipedia](https://xiaomipedia.com/en/) - Contains a lot of devices with descriptions and Product Numbers, but lack a lot models and don't have Model ID.
- [(En) Vacuum Robot Overview](https://dontvacuum.me/robotinfo/) - A detailed description of a variety of vacuum cleaners, including hardware details.
- [(En) Zigbee Device Compatibility Repository by Blakadder](https://zigbee.blakadder.com/all.html) - A lot of zigbee devices with useful information about.

---
### TODO:
- Move to XLSX
- Save order from final report in product_number manual table 
- Automaticaly add number of descriptions/models in README
- Add unused icons autoremove
- Fix VEVS package version in constants
- Move to Google Sheet with URL's pictures
- Add three Connection columns (Wi-Fi/ZigBee/BT). 
  - Examples: "2.4Ghz/5Ghz", "5.0", "3.0"
- Add Brand column
  - Examples: "MiJia", "Aqara", "QingPing Cleargrass"
- Add Year column
- Add Country column (ask vevs how to determine?)
- Add Integration column (make a script to parse) 
  https://github.com/blakadder/zigbee:
    - Wi-Fi
    - Bluetooth
    - Zigbee
        - OpenHab
        - ioBroker
            - https://github.com/ioBroker/ioBroker.zigbee
        - deConz
            - https://github.com/dresden-elektronik/deconz-rest-plugin/wiki/Supported-Devices
        - Zigbee Home Automation (ZHA)
        - Tasmota
        - Lumi Gateway
            - https://github.com/AlexxIT/XiaomiGateway3 
- Add Google Form for device addition
    


Zigbee Home Automation
Tasmota
Zigbee2MQTT
deCONZ
ZiGate
ioBroker.zigbee
