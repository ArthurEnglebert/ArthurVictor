# ArthurVictor

## info commandes
- `ethoschat` (pour l'IRC) (taper `/exit` pour quitter)
- `sudo poweroff` pour eteindre le rig (NE LE REBOOT PAS !!)
- `r` pour reboot

## info linux - eth.os
Eth.os charge des folders dans le PATH au startup, dont /opt/ethos/sbin qui contient plusieurs commandes.
La plus interessante est ethos-terminal qui affiche le terminal dans le desktop.

Eth.os charge aussi le fichier ~/custom.sh dans lequel on peut mettre des commandes.
Actuellement, j'ai mis : 
- `setxkbmap be` (set le keyboard layout à be)
- ``xrandr --output `xrandr | grep " connected" | cut -f1 -d" "` --auto`` (injecte la valeur de la commande interne pour recuperer le display actif, et demande a xrandr de l'update en auto, qui normalement fullscreen)
- `killall urxvt` (commande de eth.os pour afficher le terminal qui bug quand on rescale la resolution)
- `ethos-terminal` (pour redemarrer ce terminal)

## todo
- [extract la clé USB et en faire un ISO.](https://ubuntuforums.org/showthread.php?t=1043014)
- [setup vpn pour se connecter aux dashboard des mines etc.](https://www.howtogeek.com/60774/connect-to-your-home-network-from-anywhere-with-openvpn-and-tomato/)
- en apprendre plus sur la config powertune
- rig de 6 cartes
- RX580 Sapphire Nitro+ MAGUEL
