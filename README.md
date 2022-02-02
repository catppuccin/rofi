# Catppuccin Rofi Port

A simple but cool catppuccin port for rofi

## Credits

- [Siduck](https://github.com/siduck) I take his rofi theme and convert it to catppuccin

## Installation

Clone the repository:

```sh
git clone https://github.com/AlphaTechnolog/rofi-catppuccin ./.catppuccin-rofi
cd ./catppuccin-rofi
```

Then create the appropiate folders:

```sh
mkdir -p ~/.config/rofi ~/.local/share/rofi/themes
```

Then copy the files:

```sh
cp -r ./.config/rofi/* ~/.config/rofi
cp -r ./.local/share/rofi/themes/* ~/.local/share/rofi/themes/*
```

## Usage

Simply run `rofi -show drun`
