# OctoPrint-Helloworld

A simple plugin that controls one Philips Hue lamp.
The lamp is switched on when printing starts and (you guessed it) switched off when printing stops.

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/hixfield/octohue/archive/master.zip

This plugin requires and automatically installs the https://github.com/quentinsf/qhue packages.

## Configuration

This plugin creates to configuration settings:

### Bridge
The IP address of your Hue Bridge.

### Lamp Id
The ID of the lamp to be controlled. In the current version there is no easy way to determine this so you will have to try and test.