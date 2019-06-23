# my-mac-setup
Productivity apps and other tweaks I use to set up my Mac

## apps

* [Alfred](https://www.alfredapp.com/) - A better Spotlight with custom workflows (go to a specific Slack channel, open a Github repo in the default browser, etc.)

* [Spectacle](https://www.spectacleapp.com/) - Simple, free window resizing and positioning app

* [Contexts](https://contexts.co/) - app switcher that saves me so much mental overhead when jumping between all of my open windows

* [iStat Menus](https://bjango.com/mac/istatmenus/) - live computer stats in menubar (CPU, network, GPU, fans, etc.) plus weather, custom clock and calendar

![iStat Menus screenshot](https://bjango.com/images/mac/istatmenus6/menubars.jpg)

* [Itsycal](https://www.mowglii.com/itsycal/datetime.html) - date/time menu bar icon with a dropdown calendar - if I don't feel like paying for another iStat Menus license

![ityscal screenshot](https://www.mowglii.com/itsycal/itsycalbanner2.png)

* [Annotate](https://itunes.apple.com/us/app/annotate-capture-and-share/id918207447?mt=12) - Capture a screenshot, quickly annotate, and then put it wherever you need (clipboard, drag and drop, save to disk, upload)

* [Plug](https://www.plugformac.com/) - Play [hypemachine](https://hypem.com) on the desktop

* [YakYak](https://github.com/yakyak/yakyak) - Native google hangouts client

## tooling

* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

* [homebrew](https://brew.sh/)

* [git open](https://github.com/paulirish/git-open)

## setup

* show dotfiles in finder - (in terminal) `defaults write com.apple.finder AppleShowAllFiles YES`
* remap caps lock to escape (since the touchbar escape provides no tactile feedback) - System Preferences -> Keyboard -> Modifier Keys https://stackoverflow.com/a/40254864/5163325
* turn off paged output for git branch command: `git config --global pager.branch false`
