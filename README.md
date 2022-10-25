## Project notes
This is a fork of [Colloid icon theme](https://github.com/vinceliuice/Colloid-icon-theme), in this project you can use [Papilus icon theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) for the apps and keep **Colloid icons** of ***tray***, ***window panels*** and ***file manager sidebar's icon***.

The install process is equal to colloid icon theme as below.

## Requisites

To use 'Collirus-icon-theme' will need install the `Colloid-theme-pack` first

**Visit the Colliod-theme-pack project page:**

[https://github.com/vinceliuice/Colloid-gtk-theme](https://github.com/vinceliuice/Colloid-gtk-theme)<br/>
or<br/>
[https://github.com/vinceliuice/Colloid-kde](https://github.com/vinceliuice/Colloid-kde)

## Colloirus icon theme

![1](preview.png?raw=true)

## Example

![2](example.png?raw=true)

## Install tips

Usage:  `./install.sh`  **[OPTIONS...]**

```
-d, --dest DIR          Specify destination directory (Default: $HOME/.local/share/icons)
-n, --name NAME         Specify theme name (Default: Colloid)
-s, --scheme TYPES      Specify folder color scheme variant(s) [default|nord|dracula]
-t, --theme VARIANTS    Specify folder color variant(s) [default|purple|pink|red|orange|yellow|green|teal|grey|all] (Default: blue)
-h, --help              Show help
```
> For example: install teal nord version -> run: `./install.sh -s nord -t teal`

> For more information, run: `./install.sh -h`

![1](folder-default.png?raw=true)
![2](folder-nord.png?raw=true)
![3](folder-dracula.png?raw=true)

