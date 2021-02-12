# Awesome Rhasspy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/rhasspy/rhasspy/master/docs/img/rhasspy.svg" align="right" width="100">](https://rhasspy.readthedocs.io)

> Carefully curated list of projects and resources for the voice assistant Rhasspy

[Rhasspy](https://rhasspy.readthedocs.io) (pronounced RAH-SPEE) is an open source, fully offline set of voice assistant services for many human languages.

Note: Although I'm a Rhasspy contributor, this is not a list of projects or resources "approved" by the Rhasspy project.

## Contents

- [Official Rhasspy resources](#official-rhasspy-resources)
- [Tutorials](#tutorials)
- [Home automation integrations](#home-automation-integrations)
- [Apps and app platforms](#apps-and-app-platforms)
- [Hardware designs](#hardware-designs)
- [Miscellaneous](#miscellaneous)
- [Contribute](#contribute)
- [License](#license)

## Official Rhasspy resources

Official resources published by the Rhasspy project.

- [Documentation](https://rhasspy.readthedocs.io) - The official reference with installation instructions, tutorials, the white paper and more.
- [Forum](https://community.rhasspy.org) - The place to get help, follow announcements, show your Rhasspy projects and discuss development.
- [GitHub organization](https://github.com/rhasspy/) - The place to get the latest code for all Rhasspy components, and open issues and pull requests.

## Tutorials

Tutorials explaining how to set up Rhasspy and use it.

- [From Scratch on a Raspberry Pi](https://rhasspy.readthedocs.io/en/latest/tutorials/#from-scratch-on-a-raspberry-pi) - Official guide covering installing Rhasspy on a Raspberry Pi from scratch using Docker.
- [Getting Started Guide](https://rhasspy.readthedocs.io/en/latest/tutorials/#getting-started-guide) - Official guide stepping you through setting up Rhasspy immediately after installation.
- [Server with Satellites](https://rhasspy.readthedocs.io/en/latest/tutorials/#server-with-satellites) - Official guide stepping you through setting up Rhasspy base and satellite devices using Rhasspy's MQTT API or HTTP API.
- [DIY voice assistant](https://cstan.io/?p=11925&lang=en) - Four-part blog series with Rhasspy and Node-RED, showing you how to tell the time, the temperature (from the internet and a ESP32 temperature sensor) and bad jokes and playing internet radio.
- [Coxprod DIY - Rhasspy](https://www.coxprod.org/domotique/category/domotique/rhasspy/) - Tutorials in French about various aspects of Rhasspy.
- [Rhasspy In Depth - Sentences](https://www.youtube.com/watch?v=sWVl0ZoXZEo) - A video in which Rhasspy's developer demonstrates how you can specify your own custom voice commands.
- [Zo krijg je stembesturing op de Raspberry Pi](https://computertotaal.nl/artikelen/internet-thuis/zo-krijg-je-stembesturing-op-de-raspberry-pi/) - A tutorial in Dutch about setting up Rhasspy and handling intents with Node-RED.
- [Control Your Home with Raspberry Pi](https://koen.vervloesem.eu/books/control-your-home-with-raspberry-pi/) - A book about self-hosted home automation, dedicating the whole voice control chapter to Rhasspy.

## Home automation integrations

Projects to integrate Rhasspy with various home automation platforms.

- [JeeRhasspy](https://kiboost.github.io/jeedom_docs/plugins/jeerhasspy/fr_FR/) - Plugin to integrate Rhasspy with the home automation project Jeedom (French).
- [Rhasspy-FHEM](https://github.com/drhirn/fhem-rhasspy) - A module to integrate Rhasspy with the home automation platform FHEM using MQTT.

## Apps and app platforms

Apps (some call these "skills") that react to Rhasspy's intents.

Note: Rhasspy's app ecosystem is still in an early stage.

- [daniele-athome/hass-config](https://github.com/daniele-athome/hass-config) - AppDaemon apps for Rhasspy in a Home Assistant configuration, with an example of a countdown timer.
- [hss-server](https://github.com/patrickjane/hss-server) - Hermes Skill Server for MQTT based voice assistants.
- [hss-skill](https://github.com/patrickjane/hss-skill) - Python library to create voice apps based on hss-server.
- [node-hss-skill](https://github.com/patrickjane/node-hss-skill) - Node.js library to create voice apps based on hss-server.
- [rhasspy-hermes](https://github.com/rhasspy/rhasspy-hermes) - Python classes for Hermes protocol support in Rhasspy.
- [rhasspy-hermes-app](https://rhasspy-hermes-app.readthedocs.io) - Rhasspy's official Python library to ease creating voice apps using the Hermes protocol.
- [rhasspy_weather](https://github.com/Daenara/rhasspy_weather) - Python script that makes Rhasspy tell you the weather.

## Hardware designs

3D-printable designs for Rhasspy hardware.

- [Case Raspberry Pi 3a+ with Respeaker 2 Mic Pi Hat and Speaker](https://www.thingiverse.com/thing:4685595) - Case for Raspberry Pi 3A+ with ReSpeaker 2-Mics Pi HAT and an Adafruit 3W mono enclosed speaker.
- [Rhasspy Case (Dot) with respeaker 2 Mic Array and Speaker](https://www.thingiverse.com/thing:4704214) - Case for Raspberry Pi Zero W with ReSpeaker 2 Mic Array and a small speaker, fitting in the hole of an Amazon Echo Dot.
- [Rhasspy Satellite Case for Rpi3A+ & ReSpeaker 2-Mics Pi HAT & Speaker 3W](https://www.thingiverse.com/thing:4642517) - Case for Raspberry Pi 3A+ with ReSpeaker 2-Mics Pi HAT and an Adafruit 3W mono enclosed speaker.

## Miscellaneous

Interesting projects that don't fall in any of the previous categories.

- [HermesLedControl](https://github.com/project-alice-assistant/HermesLedControl) - Service to let the LEDs on your voice assistant hardware react to Hermes MQTT messages.
- [ESP32-Rhasspy-Satellite](https://github.com/Romkabouter/ESP32-Rhasspy-Satellite) - Standalone Rhasspy satellite for ESP32 devices such as the MATRIX Voice and M5Stack ATOM ECHO.
- [rhasspy-mobile-app](https://github.com/razzo04/rhasspy-mobile-app) - A mobile app for Android and iOS to interface with your Rhasspy installation.
- [rhasspy-watch](https://github.com/cedcox/rhasspy-watch) - Tool for dynamic display of Rhasspy's Hermes MQTT messages with recording and query functionality.
- [voice2json](https://voice2json.org/) - Rhasspy's sister project, a collection of command-line tools for offline speech and intent recognition on Linux.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Koen Vervloesem](mailto:koen@vervloesem.eu) has waived all copyright and
related or neighboring rights to this work.
