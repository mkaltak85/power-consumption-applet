# power-consumption-applet
This applet is an adaption of `temperature@fevimu` and shows the current power consumption by periodically reading 
```
/sys/class/power_supply/BAT0/power_now
```
The applet requires this file and was written for `Linux Mint 20` running `kernel 5.4` on a `Lenovo T480s`. 
The background color of the applet changes according to the settings of `low`,`high` and `critical` threshholds. 

# Installation: 
```
git clone https://github.com/mkaltak85/power-consumption-applet/ ~/.local/share/cinnamon/applets/power-consumption@mkaltak85
```
All options in the config menu of the applet (right click on the symbol in the panel) must be switched on.
The values for `low`, `high` and `critical` thresholds can be chaned in `applet.js`.  

# N.B.:
With `tlp` installed the idle power consumption is around 3 to 4 Watt. 
Also, to reduce power consumption while browsing and watching videos in the browser, take a look at https://www.linuxuprising.com/2018/08/how-to-enable-hardware-accelerated.html.

