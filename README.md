New Proxmox VM with Home Assistant
This script will create a new Proxmox VM with the latest 'haos_ova' image of Home Assistant. 

To create a new VM, run the following in a SSH session or the console from Proxmox interface

bash -c "$(wget -qLO - https://raw.githubusercontent.com/ATY77/proxmox_hassos_install/main/install_aty.sh)"
