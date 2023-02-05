# NS-Pro-Dashboard
Home Assistand Dashboard for NSPRO

Sonoff NS Pro running Home Assistant companion app natively.
I wanted to replace a light switch with a small panel and have the original 2 switch buttons replaced by the panel but also have other home controls accessed by swiping left and right. I’m very happy with the result of this small panel. the screen is clear and bright enough, looks professional and is fast enough to handle multiple pages. this is a good cost effective option for the smart home.
I use the android integration (ADB) and node red to control screen dimming, sleep and weekly reboots. Screen is waking from my mmWave and pir sensors in adjacent rooms so it appears to always be on but sleeps when away.
The Home assistant dash is made from Swiper card, Picture elements, custom thermostat card, mushroom cards and card mod to move everything around to fit the space.
Im not the best at yaml and it can be optimised for sure, please feel fee to help me out with this..

Use this guide to install Home Assistant on your NS Pro:
https://blakadder.com/nspanel-pro-sideload/
or youtube:
https://www.youtube.com/watch?v=c1Dqdz8yHDc

These custom cards that are required for my dash:
https://community.home-assistant.io/t/lovelace-swiper-card/72447
https://github.com/thomasloven/lovelace-layout-card
https://github.com/piitaya/lovelace-mushroom-themes
https://github.com/thomasloven/hass-browser_mod

