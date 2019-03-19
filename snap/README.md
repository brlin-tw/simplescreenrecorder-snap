# Unofficial Snap Packaging for SimpleScreenRecorder
<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
<img src='gui/simplescreenrecorder.png' title='Icon of SimpleScreenRecorder' alt='Icon of SimpleScreenRecorder' />

**This is the unofficial snap for SimpleScreenRecorder**, *"A feature-rich screen recorder"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `simplescreenrecorder-brlin` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/simplescreenrecorder-snap.svg "Build Status ofsimplescreenrecorder-brlin` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/simplescreenrecorder-snap)

![Screenshot of the Snapped Application](local/screenshots/welcome-screen.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal
    # Install the snap #
    sudo snap install simplescreenrecorder-brlin
    
    # Connect the snap to optional security confinement interfaces #
    ## To allow access to ALSA devices ##
    sudo snap install core
    sudo snap connect simplescreenrecorder-brlin:alsa
    
    # Launch the application #
    simplescreenrecorder-brlin
    
    ## If you have another existing installation ##
    snap run simplescreenrecorder-brlin

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/simplescreenrecorder-brlin)

## What is Working
* Launch
* PulseAudio audio capture
* ALSA audio capture
* I18N
* Builtin output profiles
* Preview pane
* Log pane
* Hotkeys
* Recording (H.264/Vorbis)

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/simplescreenrecorder-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/simplescreenrecorder-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
