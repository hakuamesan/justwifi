# JustWifi

JustWifi is a WIFI Manager library for the [Arduino Core for ESP32. The goal of the library is to manage ONLY the WIFI connection (no webserver, no mDNS,...) from code and in a reliable and flexible way.

[![version](https://img.shields.io/badge/version-2.0.3-brightgreen.svg)](CHANGELOG.md)
[![travis](https://travis-ci.org/xoseperez/justwifi.svg?branch=master)](https://travis-ci.org/xoseperez/justwifi)
[![codacy](https://img.shields.io/codacy/grade/4ccbea0317c4415eb2d1c562feced407/master.svg)](https://www.codacy.com/app/xoseperez/justwifi/dashboard)
[![license](https://img.shields.io/github/license/xoseperez/justwifi.svg)](LICENSE)
<br />

## Features

The main features of the JustWifi library are:

* Configure multiple possible networks
* Scan wifi networks so it can try to connect to only those available, in order of signal strength
* Smart Config support (when built with -DJUSTWIFI_ENABLE_SMARTCONFIG, tested with ESP32 SmartConfig or IoT SmartConfig apps)
* WPS support (when built with -DJUSTWIFI_ENABLE_WPS)
* Fallback to AP mode
* Configurable timeout to try to reconnect after AP fallback
* AP+STA mode
* Static IP (autoconnect is disabled when using static IP)
* Single debug/action callback

## Usage

See examples.

