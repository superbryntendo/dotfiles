# dotfiles

These are my personal macOS preferences with install scripts for configuring a machine as fast as possible.

# instructions

Clone or download into `~`, modify the crap out of them (they're just my prefs and yours are probably different), then run `.dotfiles/scripts/bootstrap` - this will symlink the appropriate files (anything with a .symlink extension) to your user folder. Everything else is imported or sourced from the .dotfiles directory.

Run `.dotfiles/macos/set-defaults.sh` to set some sane defaults for your computer (definitely change the computer name though unless your name is Bryn).

After that, run `.dotfiles/scripts/install` to install a decent set of apps via homebrew.

# thanks

The structure and many of the preferences came from [@holman's dotfiles](https://github.com/holman/dotfiles) with a smattering of macOS preferences from [@mathiasbynens' dotfiles](https://github.com/mathiasbynens/dotfiles) as well. Shout out to them for making it easy for an idiot like me to hit the ground running.
