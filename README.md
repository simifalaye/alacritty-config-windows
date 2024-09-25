# Alacritty Configuration For Windows

## Install

- Install the latest version of Alacritty terminal [here](https://github.com/alacritty/alacritty/blob/master/INSTALL.md)
- Install the configuration repo to `%APPDATA%/alacritty`
  - `cd /mnt/c/Users/<username>/AppData/Roaming && git clone <repo> alacritty`

## Fix Alacritty tmux rendering issue

[Source](https://github.com/alacritty/alacritty/issues/7792)

**Fix for now until issue is resolved in windows**
- Install Wezterm
- Go to it's installation folder (Most likely C:\Program Files\WezTerm)
- Copy the files `conpty.dll` and `OpenConsole.exe`
- Paste them to the installation folder of alacrity (Most likely C:\Program Files\Alacritty)
- Uninstall wezterm
