# 3DS SDL2 Packages

devkitPro packages for the 3DS versions of SDL2 packages.

## Installation

The easiest way to install SDL2 for the 3DS is by just downloading the packages
from the latest release and installing them with `(dkp-)pacman -U`.

### Manual

First you need to clone this repo with:

```sh
git clone https://github.com/gradylink/3ds-sdl2-packages
```

Then, enter the folder of the package you want to install (e.g. `cd sdl2` for
the SDL2 and `cd sdl2_mixer` for SDL2_mixer).

Lastly, run:

```sh
(dkp-)makepkg -si
```

to install the package.

## Updating

Just reinstall with the newest version.
