# power-consumption-applet
This applet shows the current power consumption by periodically reading 
```
/sys/class/power_supply/BAT0/power_now
```
The applet requires this file and was tested with `Linux Mint 20` running `kernel 5.4` on a `Lenovo T480s`. 
All options in the config menu of the applet (right click on the symbol in the panel) must be switched on.
The background color of the applet changes according to the settings of `low`,`high` and `critical` threshholds. 
