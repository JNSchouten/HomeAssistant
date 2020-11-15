[![BuyMeCoffee][buymecoffeebedge]][buymecoffee]
[![custom_updater][customupdaterbadge]][customupdater]
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Open Source Love png1](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

_Component to integrate with [Rike FireNet]._

This custom component dynamically creates sensor.afvalwijzer_* items. For me personally the items created are gft, restafval, papier, pmd and kerstbomen. Look in the states overview in the developer tools in Home Assistant what the sensor names for your region are and modify where necessary.

Special thanks go out to https://github.com/heyajohnny/afvalinfo for allowing me to copy scraper code!

**This component will set up the following platforms.**

Platform | Description
-- | --
`sensor` | Show waste pickup dates for mijnafvalwijzer.nl, rova.nl or afvalstoffendienstkalender.nl.

![example][exampleimg1]
