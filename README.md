<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for Rofi
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/rofi/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/rofi?colorA=1e1e28&colorB=c9cbff&style=for-the-badge&logo=starship style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/rofi/issues"><img src="https://img.shields.io/github/issues/catppuccin/rofi?colorA=1e1e28&colorB=f7be95&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/rofi/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/rofi?colorA=1e1e28&colorB=b1e1a6&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/catppuccin/rofi/main/.misc/screenshot.png" />
</p>

A simple but cool catppuccin port for rofi

## Credits

- [Siduck](https://github.com/siduck) I take his rofi theme and convert it to catppuccin

## Usage

First you need to install a nerd font in the [nerdfonts page](https://www.nerdfonts.com/font-downloads)
the default font is JetBrainsMono Nerd Font, but you can install another and then edit the theme
to set it

The file you need to edit is `.config/rofi/config.rasi` and change JetBrainsMono Nerd Font
to your font.

Clone the repository:

```sh
git clone https://github.com/catppuccin/rofi ./.catppuccin-rofi
cd ./.catppuccin-rofi
```

Then create the appropiate folders:

```sh
mkdir -p ~/.config/rofi ~/.local/share/rofi/themes
```

Then copy the files:

```sh
cp -r ./.config/rofi/* ~/.config/rofi
cp -r ./.local/share/rofi/themes/* ~/.local/share/rofi/themes/
```

Then simply run `rofi -show drun`

## 💝 Thanks to

- [AlphaTechnolog](https://github.com/AlphaTechnolog)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=302d41&colorB=c9cbff"/></a></p>


