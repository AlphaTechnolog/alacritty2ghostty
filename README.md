# Alacritty 2 Ghostty

Little script that converts alacritty themes into ghostty themes

## Example usage

### From local file

```sh
wget https://raw.githubusercontent.com/alacritty/alacritty-theme/refs/heads/master/themes/ashes_dark.toml
./alacritty2ghostty ./ashes_dark.toml
```

Outputs

```
background = #161616
foreground = #c7ccd1
palette = 0=#1c2023
palette = 1=#c7ae95
palette = 2=#95c7ae
palette = 3=#aec795
palette = 4=#ae95c7
palette = 5=#c795ae
palette = 6=#95aec7
palette = 7=#c7ccd1
palette = 8=#747c84
palette = 9=#c7ae95
palette = 10=#95c7ae
palette = 11=#aec795
palette = 12=#ae95c7
palette = 13=#c795ae
palette = 14=#95aec7
palette = 15=#f3f4f5
```

### From network

```sh
./alacritty2ghostty https://raw.githubusercontent.com/alacritty/alacritty-theme/refs/heads/master/themes/ashes_dark.toml
```

Outputs

```
background = #161616
foreground = #c7ccd1
palette = 0=#1c2023
palette = 1=#c7ae95
palette = 2=#95c7ae
palette = 3=#aec795
palette = 4=#ae95c7
palette = 5=#c795ae
palette = 6=#95aec7
palette = 7=#c7ccd1
palette = 8=#747c84
palette = 9=#c7ae95
palette = 10=#95c7ae
palette = 11=#aec795
palette = 12=#ae95c7
palette = 13=#c795ae
palette = 14=#95aec7
palette = 15=#f3f4f5
```

> [!TIP]
> You can then redirect the stdout to your ghostty config in append mode by using `alacritty2ghostty <input> >> ~/.config/ghostty/config`

> [!TIP]
> Use the `--comments` flag to add comments about every color in the output.

## Installation

Clone the repository and install the requirements

```sh
git clone https://github.com/alphatechnolog/alacritty2ghostty.git --depth=1 alacritty2ghostty
cd alacritty2ghostty
./alacritty2ghostty --help
```

## Support this

If you think this little script is useful for your usage, please consider giving me a star :D
