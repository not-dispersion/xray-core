# **Xray Core** (Minimal Setup)
A fully automated, minimal installation script for Xray + Reality with TCP transport.
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

```newuser``` - Add a new user \
```userlist``` - List all users \
```rmuser``` - Remove a user \
```sharelink``` - Get connection link for existing user

**IMPORTANT! Always run these commands as root to ensure they work correctly.**

I'll add the uninstallation script in future updates.