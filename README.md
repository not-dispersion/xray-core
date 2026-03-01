# **Xray Core** (Minimal Setup)
A fully automated minimal Xray + REALITY installation script for Debian-based systems (TCP transport).
No web panels. No unnecessary components. Just the core. \
This script will also create management commands to easily handle users.
## Installation
Run the following command with root privileges (```sudo```).
The ```wget``` package must be installed.
```
wget -qO- https://raw.githubusercontent.com/not-dispersion/xray-core/refs/heads/main/xray-core-install | sudo bash
```
## User Management Commands
All management commands must be executed with root privileges (sudo):

```newuser``` - add a new user \
```userlist``` - list all users \
```rmuser``` - remove a user \
```sharelink``` - get connection link for existing user

**IMPORTANT! Always run these commands as root to ensure they work correctly.**

I'll add the uninstallation script in future updates.