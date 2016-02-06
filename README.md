![screenshot](https://luz.lu/tewi/tewi.png)

# Glyphs
### tewi-normal
![tewi-normal](https://luz.lu/tewi/tewi-normal.png)

### tewi-bold
![tewi-bold](https://luz.lu/tewi/tewi-bold.png)

### tewi2a-normal
![tewi2a-normal](https://luz.lu/tewi/tewi2a-normal.png)

### tewi2a-bold
![tewi2a-bold](https://luz.lu/tewi/tewi2a-bold.png)

### tewifw-normal
![tewifw-normal](https://luz.lu/tewi/tewifw-normal.png)

### tewifw-bold
![tewifw-bold](https://luz.lu/tewi/tewifw-bold.png)

# Installation
### Gentoo
[lucy/lucy-overlay](https://github.com/lucy/lucy-overlay) contains an
up-to-date ebuild.

### Arch
Has an [aur package](https://aur.archlinux.org/packages/bdf-tewi-git/).

### X11
```
$ make fontdir
$ xset +fp /path/to/tewi-font/out
```

### Fontconfig
```
$ make
$ ln -s /path/to/tewi-font/out ~/.fonts/tewi
```

# Variants
tewi2a needs tewi as a fallback.
tewifw is meant to be used after the others.


# CJK Fallbacks
mplus, kochi gothic and wqy-bitmapfont are good. wqy is broken in urxvt.
