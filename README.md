# Crystal Linux [GRUB](https://gnu.org/software/grub/) Theme

> A customised theme for [GRUB](https://gnu.org/software/grub/) using the Crystal Linux branding.

![image](https://user-images.githubusercontent.com/30374463/189643831-6e29a350-a57d-4aa6-902a-ea08b527cc39.png)

## Install (Arch-based ONLY)

- Clone the PKGBUILD and enter the directory:
```bash
git clone https://github.com/crystal-linux/pkgbuild.grub-theme
cd pkgbuild.grub-theme
```

- Run `makepkg` to install it:
```
makepkg -si
```

- Append the following text to `/etc/default/grub`:
```
GRUB_THEME="/usr/share/grub/themes/crystal/theme.txt"
```

## Team

This theme is based on the Dracula Dark theme for GRUB, created by the following person(s) and a bunch of [awesome contributors](https://github.com/dracula/grub/graphs/contributors).

[![Zeno Rocha](https://github.com/pspiagicw.png?size=100)](https://github.com/pspiagicw) |
--- |
[Zeno Rocha](https://github.com/pspiagicw) |

## License

[MIT License](./LICENSE)
