# rulah-net-config
Notes and scripts to get Rulah back online!


<img src="https://raw.githubusercontent.com/roboskel/rulah-net-config/master/media/arch.png" width=50%>

### PC Config
<img src="https://raw.githubusercontent.com/roboskel/rulah-net-config/master/media/general_setup.png" width=100%>
<img src="https://raw.githubusercontent.com/roboskel/rulah-net-config/master/media/eth_config.png" width=100%>

WLAN configuration should left with the default configuration (no need for a static IP)

### Picostation Config

The picostation should be configured as an Access Point (AP).

<img src="https://raw.githubusercontent.com/roboskel/rulah-net-config/master/media/picostation_config.png" width=50%>

### Using the PC as a Router

After configuring all the above, the `rc.local` script should be placed under the `/etc` folder of the Intel NUC, with 755 permissions. After placing the script a simple reboot or execution of the script should allow for all devices connected to Rulah's private network to have internet access!