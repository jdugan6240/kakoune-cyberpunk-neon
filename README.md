# kakoune-cyberpunk-neon
Port of [Roboron3042's Cyberpunk Neon theme](https://github.com/Roboron3042/Cyberpunk-Neon) for Kakoune

Supports the following plugins:
* [powerline.kak](https://github.com/andreyorst/powerline.kak)
* [kak-crosshairs](https://github.com/insipx/kak-crosshairs)
* [kakoune-roguelight](https://github.com/occivink/kakoune-roguelight)
* [kak-rainbow](https://github.com/Bodhizafa/kak-rainbow)

## Screenshot
![Screenshot](/screenshots/cyberpunk-neon-code.png "Example of the colorscheme in use")

# Installation
### [Plug.kak](https://github.com/andreyorst/plug.kak)
Put the following in your kakrc:

    plug Anomalocaridid/kakoune-cyberpunk-neon theme config %{
        colorscheme cyberpunk-neon
    }

### Manual installation
Copy the `cyberpunk-neon.kak` file into `~/.config/kak/colors` and put `colorscheme cyberpunk-neon` in your kakrc.

### Enabling powerline support
Configure the powerline plugin in your kakrc like so:

    plug andreyorst/powerline.kak defer powerline %{
        powerline-theme cyberpunk-neon
    } config %{
        powerline-start
    }
