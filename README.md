<div align="center">

# eza themes

Themes for [eza](https://github.com/eza-community/eza).

</div>

**DISCLAIMER:** This is work-in-progress and thus still private until the recently
merged theming feature is released and stabilized a bit more. Also we have to
come up with a couple of themes first.

## Themes

- [default](themes/default.yml): Replicates eza's default look.
- [black](themes/black.yml): All black everything.
- [white](themes/white.yml): All white everything.

**NOTE:** Before adding new themes, a PR for improving eza's color deserialization
including hex color specification is planned, which would simplify theming
with concrete RGB values a lot. So maybe wait for that first.

## Installation

On Linux, simply clone the repository somewhere and symlink a theme to
`~/.config/eza/theme.yml`:
```sh
git clone https://github.com/eza-community/eza-themes.git
mkdir -p ~/.config/eza
ln -s "$(pwd)/eza-themes/themes/default.yml" ~/.config/eza/theme.yml
```
