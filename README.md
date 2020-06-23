# Maswerasei

A websocket client in flutter making use of [Janus](https://github.com/meetecho/janus-gateway) [SIP plugin](https://janus.conf.meetecho.com/docs/sip.html)

## Overview of Project
- use of [flutter]() to build basic dialpad and registration page
- SIP over Websockets for signalling
- Audio handled by ([flutter-webrtc](https://github.com/cloudwebrtc/flutter-webrtc))
- Tested with OpenSIPS, Freeswitch.
- Should also work with Kamalio and Asterisk (TODO) 

## Setup and Installation
- ensure that you have flutter installed and and emulator to test
- verfiy everything is ok
```
flutter doctor
```
- get project
```
git clone https://github.com/chikondot/maswerasei.git
cd maswerasei
```
- build/run project
```
flutter clean
flutter pub get
flutter run
```
- application should have opened within emulator/device
- please note to allow permissions for calling and audio
- presented with sceen below:

![Image of Homepage](https://github.com/chikondot/maswerasei/blob/master/images/homepage.png)

## Supported and Tested Platform
- [X] iOS && Android (Mobile)
- [] Chrome, macOS, Firefox (Web)

## License
maswerasei is released under the [MIT license](https://github.com/chikondot/masweraei/blob/master/LICENSE).
