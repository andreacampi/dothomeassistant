# home-automation

This repo contains configurations and other bits for my home automation setup.

* [ESPHome](https://esphome.io) configuration files in the esphome subdirectory:
  * Installed on an [ATOM Lite ESP32 IoT Development Kit](https://m5stack.com/products/atom-lite-esp32-development-kit) (Pimoroni is a better [source](https://shop.pimoroni.com/products/atom-lite-esp32-development-kit) in the UK).
  * Xiaomi Flora Plant Monitor devices (multiple)
* [Mosquitto](http://mosquitto.org) configuration files in the mosquitto subdirectory:
  * running on a [Synology DS218+](https://www.synology.com/en-uk/products/DS218) NAS
  * installed [directly](https://gist.github.com/ajumalp/0ad2517d15c999cfc440cdf3d623fab8). TODO move to Docker
* [Home Assistant](https://www.home-assistant.io) configuration files in the homeassistant subdirectory:
  * running on a [Synology DS218+](https://www.synology.com/en-uk/products/DS218) NAS (see the [documentation](https://www.home-assistant.io/docs/installation/docker/#synology-nas) for how to run in Docker).
* Prometheus / Grafana stack in the homeassistant subdirectory:
  * installed via [synology-prometheus](https://github.com/prahaladramji/synology-prometheus)
