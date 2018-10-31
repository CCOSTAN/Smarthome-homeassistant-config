# Smart Home - Home Assistant

Home Assistant is a home automation platform running on Python 3. It is
able to track and control all devices at home and offer a platform for
automating control.

## Current Configuration

- RaspberryPi 3B+ using the Hassbian installation -\>
    (<https://home-assistant.io/docs/installation/hassbian/>).
- Using also the Lovelace UI -\>
    (<https://www.home-assistant.io/lovelace/>).

## Information

| [![Travis CI][travis-shield]][travis] | [![GitHub Last Commit][last-commit-shield]][commits]|
|:---:|:---:|
| This shows whether the configuration in this repo is valid | This shows how up to date this repo is |
| [![GitHub Stars][stars-shield]][stars] | [![HA Version][ha-version-shield]][home-assistant] |
| Please :star: this repo if you find it useful, like these people have | This is the version that I am currently running with Home Assistant |
| [![Uptime Robot status][uptime-shield]][uptime-robot] | [![GitHub Activity][commits-shield]][commits] |
| I use Uptime Robot to monitor my instance from outside in case of crashes | Shows how active I am with this repo annually |

## Hardware

I use a raspberry pi 3rd generation to run home assistant. In addition,
I use a Z-wave stick to control devices that use the z-wave protocol and
an RFX module for controlling devices that work on the 433mhz frequency
band. Because the raspberry pi is hanging in the meter closet, the smart
meter is also read via a P1 cable.

- Raspberry PI 3B+
- Aeotec USB Z-Stick - Z-Wave Plus -\>(<https://aeotec.com/z-wave-usb-stick>)
- RFXCOM RFXtrx433E -\>(<http://www.rfxcom.com/store/Transceivers/14103>)
- P1 cable -\> (<https://www.sossolutions.nl/slimme-meter-kabel>)

## Devices

- FIBARO Smoke sensors
- FIBARO Door sensors
- FIBARO Motion sensors
- FIBARO Wall plug
- KlikAanKlikUit devices (CoCo)
- DSMR (Smart meter)
- Google Chromecast
- Philips TV
- Water fountain in the garden
- Yeelights
- Teclast P80 Pro
- Google home (mini)

## Apps

- HomeAssist (for android) -\>(<https://play.google.com/store/apps/details?id=com.axzae.homeassistant&hl=nl>)
- Home Assistant (for iOS) -\>(<https://www.home-assistant.io/docs/ecosystem/ios/>)
- Home Assistant (As web app) -\>(<https://www.home-assistant.io/docs/frontend/mobile/>)

## Needing Help?

- Home Assistant Homepage -(<https://home-assistant.io/>)
- Home Assistant Forums -(<https://community.home-assistant.io/>)
- Home Assistant Discord Chat -(<https://discord.gg/c5DvZ4e>)
- Other Featured Home Assistant Configurations-(<https://home-assistant.io/cookbook/>)
- Home Assistant GitHub Source Repository-(<https://github.com/home-assistant/home-assistant>)
- Official Home Assistant Demo -(<https://home-assistant.io/demo/>)

[commits-shield]: https://img.shields.io/github/commit-activity/y/klaasnicolaas/smarthome-homeassistant-config.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/klaasnicolaas/Smarthome-homeassistant-config.svg?color=blue&style=plasticr
[travis-shield]: https://travis-ci.org/klaasnicolaas/Smarthome-homeassistant-config.svg?branch=master
[stars-shield]: https://img.shields.io/github/stars/klaasnicolaas/Smarthome-homeassistant-config.svg
[ha-version-shield]: https://img.shields.io/badge/Home%20Assistant-0.80.0-blue.svg
[uptime-shield]: https://img.shields.io/uptimerobot/status/m781145866-63b6526d17827ec6eebe586f.svg
[gitlabci-shield]: https://gitlab.com/klaasnicolaas/Smarthome-homeassistant-config/badges/master/pipeline.svg

[commits]: https://github.com/klaasnicolaas/Smarthome-homeassistant-config/commits/master
[travis]: https://travis-ci.org/klaasnicolaas/Smarthome-homeassistant-config
[stars]: https://github.com/klaasnicolaas/Smarthome-homeassistant-config/stargazers
[home-assistant]: https://home-assistant.io
[uptime-robot]: https://uptimerobot.com
[gitlabci]: https://gitlab.com/klaasnicolaas/Smarthome-homeassistant-config/pipelines