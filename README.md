# my-mac-setup
Productivity apps and other tweaks I use to set up my Mac

## apps

* [MeetingBar](https://github.com/leits/MeetingBar) - Show upcoming meetings in menubar, and join from context menu

* [Contexts](https://contexts.co/) - app switcher that saves me so much mental overhead when jumping between all of my open windows

* [Spectacle](https://www.spectacleapp.com/) - Simple, free window resizing and positioning app

* [Itsycal](https://www.mowglii.com/itsycal/datetime.html) - date/time menu bar icon with a dropdown calendar
![ityscal screenshot](https://www.mowglii.com/itsycal/itsycalbanner2.png)

* [Plug](https://www.plugformac.com/) - Play [hypemachine](https://hypem.com) on the desktop

* [Alfred](https://www.alfredapp.com/) - A better Spotlight with custom workflows (go to a specific Slack channel, open a Github repo in the default browser, etc.)

### Apps I've Used Before but don't any more

* [iStat Menus](https://bjango.com/mac/istatmenus/) - live computer stats in menubar (CPU, network, GPU, fans, etc.) plus weather, custom clock and calendar. This was too much for me, the only thing I found myself using was the calendar, which itsycal does just as well, for free

![iStat Menus screenshot](https://bjango.com/images/mac/istatmenus6/menubars.jpg)

* [Annotate](https://itunes.apple.com/us/app/annotate-capture-and-share/id918207447?mt=12) - Capture a screenshot, quickly annotate, and then put it wherever you need (clipboard, drag and drop, save to disk, upload). I think this apps has stopped working, and my current job pays for CloudApp, which does the same thing.

* [YakYak](https://github.com/yakyak/yakyak) - Native google hangouts client. This breaks continuously as it uses reverse engineered Google APIs, it's easier to just use the browser hangouts interface instead of constantly checking github issues to see when the latest bug will be fixed.

* [SoundSource](https://rogueamoeba.com/soundsource/) - Control external HDMI devices with keyboard controls (among many other things). I needed this for my last monitor, I don't have issues with my current setup that the native mac controls can't handle.

## tooling

* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

* [homebrew](https://brew.sh/)

* [git open](https://github.com/paulirish/git-open)

## setup

* show dotfiles in finder - (in terminal) `defaults write com.apple.finder AppleShowAllFiles YES`
* remap caps lock to escape (since the touchbar escape provides no tactile feedback) - System Preferences -> Keyboard -> Modifier Keys https://stackoverflow.com/a/40254864/5163325
* turn off paged output for git branch command: `git config --global pager.branch false`
