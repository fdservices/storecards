# Store Cards

Store Cards is built using Tcl/TK and Zint

The aim is to keep all your store cards on your linux phone.

## Requirements
The only dependencies are tcl, tk and zint.

## Optional Dependencies
Sane (scanimage) and Imagemagick (magick) to allow scanning of Store Cards

Imagemagick (magick) to read and convert different image types.

Pinephone-Toolkit (pptk) to raise the backlight for easy scanning of barcodes ([AUR](https://aur.archlinux.org/packages/pinephone-toolkit-git/) or https://github.com/Dejvino/pinephone-toolkit)

## Installaton

Download the source code and run install.sh to:

	Copy the storecards programme to /usr/bin

	Copy the icons to /usr/share/pixmaps/storecards

	Copy the desktop file to /usr/share/applications

	Copy the sample data files to ~/.local/share/storecards

To update download the source code and run install.sh again. all data will be preserved.

To uninstall Store Cards run uninstall.sh from the downloads directory.


This is the first release of the software. If you find it useful, good. If you do not then please file a bug report.
