[![](logo.png)](https://www.signal.org/)

# Signal Messenger

Rest-API to Signal-CLI Home Assistant add-on

# How to use this add-on

Install the add-on, choose your desired port, start.

After the add-on is started follow the directions at the link below starting from "Register phone number"

https://github.com/bbernhard/signal-cli-rest-api/blob/master/doc/HOMEASSISTANT.md

Then proceed here:

https://www.home-assistant.io/integrations/signal_messenger/

# API details

If you want to use i.e. REST to receive messages in HA, you can find more details [here](https://bbernhard.github.io/signal-cli-rest-api/)

It is highly suggested that you use the machine IP address, rather than the loopback address mentioned in the upstream container documentation to register numbers. In HAOS everything is containerized and loopback addresses stay inside the respective containers.

# Disclaimer

All credit to [@bbernhard](https://github.com/bbernhard) and [haberda](https://github.com/haberda/hassio_addons) for the addon.

all I did was fork it and tailor it over better overview for me.
