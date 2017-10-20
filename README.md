# OctoPrint PSU Control OPi
This OctoPrint plugin controls an ATX/AUX power supply to help reduce power consumption and noise when the printer is not in use.

Power supply can be automatically switched on when user specified commands are sent to the printer and/or switched off when idle.

Supports Commands (G-Code or System) or GPIO to switch power supply on/off.

This fork has been created for being able to run OctoPrint PSU Control on a Orange Pi Zero (or simliar) board.

The library used for controlling the GPIO pins is [orangepi_PC_gpio_pyH3](https://github.com/duxingkei33/orangepi_PC_gpio_pyH3)

**Requires a Orange Pi board**

![PSUControl](psucontrol_navbar_settings.png?raw=true)
 
 
## Setup

Install the plugin using Plugin Manager from Settings
 
## Settings
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/Settings)
 
## Troubleshooting
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/Troubleshooting)

## API
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/API)
