MagickShot – ImageMagick Screenshot
================

## Contents

-   [Usage](#usage)
-   [Dependencies](#dependencies)
-   [Installation](#installation)
    -   [Universal](#universal)
    -   [Gentoo](#gentoo)
-   [Uninstallation](#uninstallation)
    -   [Universal](#universal-1)
    -   [Gentoo](#gentoo-1)

MagickShot is a program to take screenshots using ImageMagick. It is
more minimal than using scrot but more convenient than using
ImageMagick. It is the perfect balance between the two.

## Usage

``` sh
`# user` magickshot -s # take a screenshot of the selection
`# user` magickshot -w # take a screenshot of the specied window (default is root)
`# user` magickshot -sw # select and screenshot a window
```

## Dependencies

1.  ImageMagick

## Installation

### Universal

``` sh
`# user` git clone https://github.com/amarakon/magickshot
`# user` cd magickshot
`# root` make install
```

### Gentoo

``` sh
`# root` eselect repository add amarlay git https://github.com/amarakon/amarlay
`# root` emerge --sync amarlay
`# root` emerge media-gfx/magickshot
```

## Uninstallation

### Universal

``` sh
`# user` cd magickshot
`# root` make uninstall
```

### Gentoo

``` sh
`# root` emerge -c media-gfx/magickshot
# Remove my overlay (optional)
`# root` eselect-repository remove -f amarlay
`# root` emerge --sync
```
