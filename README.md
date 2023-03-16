### Metasploit Framework 6 in Termux


![Metasploit 6 running](https://i.imgur.com/yLFQhvP.png)

## How to Install
## Before

In order to have updated Termux:
- **Purge all data** of Termux in Android Settings
- Uninstall and reinstall latest Termux version from [F-Droid](https://f-droid.org/en/packages/com.termux/) (Version on Play Store is outdated)
- Then launch Termux to initialization, close it (force stop, not swap)
- Reopen and follow the instructions below

### Auto
```bash
source <(curl -fsSL https://kutt.it/msf)
```

### Manual
```bash

pkg install wget

wget https://github.com/U7P4L-IN/Metasploit/raw/main/metasploit.sh


chmod +x metasploit.sh

./metasploit.sh
```

## Launch metasploit
After installation complete execute:
```bash
msfconsole
```
