## Update
Our service is constantly being developed and updated. This means that as soon as a new service is added to our offer or an existing list is extended, the config file on the client side needs to be updated.

!!! INFO
    
    You can see these updates in the [`#changelog`]() room!

!!! DANGER "Important!"

    Whichever solution you use; you will end up having to delete the config from Wireguard and then add it again!

There are 3 ways to do this, starting with the simplest. This works if, for example, only 2 domains are included in a list, or even a new one, for example:
```
10.20.30.0/24, 20.30.40.0/24
```
In that case, you can open your config with a text editor and add them to the end of the `AllowedIPs` line (after the many ip).

But most of you don't want to have to dig around in the file, there are two other solutions.

## Website

The simpler solution is the [update website](https://update.fxtelekom.org/).

You can simply paste your config here and you will always get the latest version, which you can then save.

![](assets/update1.png)

![](assets/update2.png)

## Powershell script

!!! INFO

    This guide is for Windows users, but this solution is platform independent, just like the others!

This may seem the scariest at first, but in this case you really don't need to open the config. Simply open a powershell or windows terminal for win 11 and copy the line below:
```
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/FXTELEKOM/IpUpdater/main/IpUpdate.ps1') }"
```

Once the program has started, just follow the instructions!

1. Add the path to your config (it won't look like this on Windows!)
![](assets/ps1.png)

2. In the menu, use the arrow keys to navigate and select what you want to send over the VPN. The service is modular and can be used in any partition.

!!! INFO

    With the "Select All" menu you can select everything!

!!! DANGER "Be careful!"
    
    If you want to select something, press `space`, only press `enter` at the end!

![](assets/ps2.png)

In case of a successful run you should get a similar output!

!!! INFO

    If you see red text, don't hesitate to visit us on Discord!
![](assets/ps3.png)
