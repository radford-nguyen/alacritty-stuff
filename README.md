alacritty-stuff
===============

My config files for the [alacritty][1] terminal emulator.

Install
-------

Clone this repo:

```bash
git clone <repo> ~/.config/alacritty-stuff
```

Create your alacrity config file and import the configs.  The
location of the [alacrity config file][2] is OS-dependent.

```toml
[general]
  import = [
    "~/.config/alacritty-stuff/base.toml",
    "~/.config/alacritty-stuff/font.toml",

    # external theme imported here:
    "~/.config/alacritty-theme/themes/everforest_dark.toml",
  ]

  live_config_reload = true
```

[1]: https://alacritty.org
[2]: https://alacritty.org/config-alacritty.html#location
