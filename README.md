# FiveM Auto Installation

This script allows for the automatic installation of a FiveM server on Linux (Debian/Ubuntu).

## Installation

Run the following command on your server (as root):

```bash
apt update -y && apt full-upgrade -y && apt install curl -y && apt install screen -y && bash <(curl -s https://raw.githubusercontent.com/LucasCFXHosting/autoinstallationfvm/refs/heads/main/setup.sh)
```
