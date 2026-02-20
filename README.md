# Fixedsys Excelsior Nerd Font

A [Nerd Font](https://www.nerdfonts.com/) patched version of **Fixedsys Excelsior**, the classic bitmap-style monospaced font originally inspired by the Windows system font.

## About

This is the non-Mono variant, meaning:

- **Letters and symbols** are monospaced (fixed-width), as expected from Fixedsys Excelsior.
- **Nerd Font icons** retain their natural width instead of being forced into a single cell.

This gives you a proper monospaced coding font with clean, full-size icons — no squished glyphs.

## Font Details

| Property    | Value                            |
| ----------- | -------------------------------- |
| Family      | FixedsysExcelsior Nerd Font      |
| Style       | Regular                          |
| Version     | 3.022 (Nerd Fonts 3.4.0 patch)   |
| Format      | TrueType (.ttf)                  |
| Glyphs      | 16,064                           |
| Em Size     | 160                              |

## Installation

### Linux

```bash
mkdir -p ~/.local/share/fonts
cp FixedsysExcelsiorNerdFont-Regular.ttf ~/.local/share/fonts/
fc-cache -fv
```

### macOS

Double-click the `.ttf` file and click "Install Font", or copy it to `~/Library/Fonts/`.

### Windows

Right-click the `.ttf` file and select "Install" or "Install for all users".

## Usage with Kitty

```conf
font_family FixedsysExcelsior Nerd Font
```

## License

Fixedsys Excelsior was created by Darien Valentine. Nerd Font icons are patched using the [Nerd Fonts Patcher](https://github.com/ryanoasis/nerd-fonts).
