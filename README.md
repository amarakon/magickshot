# MagickShot – ImageMagick Screenshot

MagickShot is a program to take screenshots using ImageMagick.
It is more minimal than using scrot but more convenient than using ImageMagick.
The usage is very simple:
* `$ magickshot` – take a screenshot of the entire screen
* `$ magickshot -s` – take a screenshot of the selection

## Dependencies
1. imagemagick

## (Un)Installation
### Universal
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Git clone the repository.
* `$ git clone https://github.com/Amarakon55/magickshot`
2. Change working directory to *magickshot*.
* `$ cd magickshot`
3. Install MagickShot using the Makefile
* `# make install`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Change working directory to *magickshot*.
* `$ cd magickshot`
2. Uninstall MagickShot using the Makefile
* `# make uninstall`

### Gentoo
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Add my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using [eselect-repository](https://packages.gentoo.org/packages/app-eselect/eselect-repository)
* `# eselect repository add amarlay git https://github.com/Amarakon55/amarlay`
2. Sync my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using `emerge`
* `# emerge --sync amarlay`
3. Emerge the MagickShot package
* `# emerge media-gfx/magickshot` or `# emerge magickshot`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Unmerge the MagickShot package
* `# emerge -c media-gfx/magickshot` or `# emerge -c magickshot`
2. (Optional) Remove my overlay
* `# eselect-repository remove -f amarlay`
3. (Optional) Sync using `emerge`
* `# emerge --sync`
