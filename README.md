# Pauline audio appliance

This is the build code for the Pauline audio appliance.

The system is configured to pass all audio through Pulseaudio.

This includes Mopidy with Iris, Soma, Tunein, and Internet archive
sources as well as Raspotify, and Zeroconf/Pulseaudio sinks.

The interface default port is currently 6680 (HTTP). If you need
IPv6, please edit pauline.yaml and comment out the code to disable
IPv6 (it's a single stanza).

Requirements

 - A Raspberry Pi 3
 - A vanilla Raspbian Buster image

# Copyright

Copyright (c) 2019, Mark Meyer (mark@ofosos.org)

