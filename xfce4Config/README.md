
## This Script Automatically set the InterfaceName for netload plugin for Xfce4 panel

### This script triggers when NetworkManager connects to a network Interface

first enable service `NetworkManager-dispatcher.service`

move this script to `/etc/NetworkManager/dispatcher.d/`
change its user and group ownership to root set permission to 755

```bash
10        user="sourav" # Change User name to yours
```

For more information check :
 [NetworkManager-1](https://www.linuxsecrets.com/archlinux-wiki/wiki.archlinux.org/index.php/NetworkManager.html)
[NetworkManager-2](https://wiki.archlinux.org/index.php/NetworkManager)

If someone want change the conept, check : 
[Various_Triggering-1](https://askubuntu.com/questions/436943/how-to-run-a-script-when-there-is-a-change-in-your-local-ip) 
[Various_Triggering-2](https://askubuntu.com/questions/258580/how-to-run-a-script-depending-on-internet-connection)