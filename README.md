# Metasploit-Termux
Install Metasploit in Termux using this Script..
Just run this script & this script will take care of the rest.. :)

## How to Install:-

## Before

In order to have updated Termux:
- **Purge all data** of Termux in Android Settings
- Uninstall and reinstall latest Termux version from [F-Droid](https://f-droid.org/en/packages/com.termux/) (Version on Play Store is outdated)
- Then launch Termux to initialization, close it (force stop, not swap)
- Reopen and follow the instructions below

### Auto
```bash
source <(curl -fsSL https://github.com/Bhartiya-Hacker/Metasploit-Termux/blob/main/metsploit.sh) 
```

### Manual
```bash
pkg install wget
wget https://github.com/Bhartiya-Hacker/Metasploit-Termux/blob/main/metsploit.sh
chmod +x metasploit.sh
./metasploit.sh
```

## Launch metasploit
After installation complete execute:
```bash
msfconsole
```

