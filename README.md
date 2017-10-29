# gabrielknight-dosbox
Configuration Files for properly running the 90's adventure Gabriel Knight on Dosbox (on Linux)

This repository covers the version from GOG.com.

Buy it here: https://www.gog.com/game/gabriel_knight_sins_of_the_fathers

## Usage

* Download the Setup files for Windows from GOG.com.
* Extract the installer, for example with innoextract
* Copy / Move  the "app" directory if needed. This directory contains all necessary Files
* Copy the config files from this repository and overwrite the ones by GOG

## What has changed?

### RESOURCE.CFG

The audio driver has been changed to ADL.DRV because the GENMIDI.DRV does not really work out of the box. It may work if you configure MIDI on your system, i have not tried it.

### dosboxGK.conf

Not much changed here, except set the audio blocksize to 1024 to avoid some sound problems.

### dosboxGK_single.conf

I changed the commands to change directory and for mounting the GOG provided image file to operate in one directory. GOG provides Dosbox with all it's games using it, but some of you might prefer having a local installation.
