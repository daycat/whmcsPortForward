# whmcsPortForward

A Usable fork of https://github.com/xieruan 's WHMCS Port Forward Plugin.

[Telegram Chat](https://t.me/whmcsCN)

## Prerequisites
1. For all servers acting as the slave / pf server, it *MUST* have CentOS 7 installed
2. You *MUST* have a server running WHMCS "Obviously"
  - Only WHMCS 8.1.3 has been tested for compatibility. If any compatibility issues are found, please PM me by Telegram @daycat or open a new issue

## Installation
### For servers acting as the slave / pf server:
```
bash <(curl -Ls https://ghproxy.com/https://raw.githubusercontent.com/daycat/whmcsPortForward/main/installx.sh)
```
Follow instructions within the script.

### For Panel:
Download this repository. Upload the Modules folder to the WHMCS server.
Then, go to Addons -> PortForward to set up the panel.
