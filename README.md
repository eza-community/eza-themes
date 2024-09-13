<div align="center">

# eza themes

Themes for [eza](https://github.com/eza-community/eza).

</div>

**DISCLAIMER:** This is work-in-progress and thus still private until the recently
merged theming feature is released and stabilized a bit more. Also we have to
come up with a couple of themes first.

## Themes

- [default](themes/default.yml): Replicates eza's default look.

<img src="imgs/default.png" alt="default theme" width="500" />

- [frosty](themes/frosty.yml): Bright and icy tones.

<img src="imgs/frosty.png" alt="frosty theme" width="500" />

- [black](themes/black.yml): All black everything.

<img src="imgs/black.png" alt="black theme" width="500" />

- [white](themes/white.yml): All white everything.

<img src="imgs/white.png" alt="white  theme" width="500" />

- [gruvbox](themes/gruvbox.yml): Classic bright theme, with warm 'retro groove' colors.

<img src="imgs/gruvbox.png" alt="gruvbox theme" width="500" />

- [catppuccin](themes/catppuccin.yml): [Catppuccin](https://catppuccin.com/palette) theme

<img src="imgs/catppuccin.png" alt="catppuccin theme" width="500" />

## Installation

On Linux, simply clone the repository somewhere and symlink a theme to
`~/.config/eza/theme.yml`:
```sh
git clone https://github.com/eza-community/eza-themes.git
mkdir -p ~/.config/eza
ln -sf "$(pwd)/eza-themes/themes/default.yml" ~/.config/eza/theme.yml
```


## Usage Hints

### Overriding Things

The theme file overrides the default styles, meaning you only need to specify
what you want to change.

### Environment Variables

`EZA_CONFIG_DIR` can be used to specify a custom configuration directory.
Also, `LS_COLORS` and `EZA_COLORS` take precedence over the theme file, so make
sure to unset them when using a theme file.

## Specification

### General
TODO

### Style
TODO

### Color
TODO

### File- and Extension-Based Overrides
TODO
