# Mac OS X iTerm2 Settings

## Installation
You can run the included bash script to install or update your preferences.
Note that iTerm.app could overwrite your preferences when it exits so there
are some checks to make sure it's doing it's work cleanly.

Note that these settings assume that the *Menlo* font is already
installed. To download and install, simply use [Homebrew](http://brew.sh/):

```sh
brew tap caskroom/fonts
brew cask install font-menlo-for-powerline
```

Install iTerm.app:

```sh
brew cask install iterm2
```

Install the settings:

```sh
curl -L https://raw.github.com/italodr/macosx-iterm2-settings/master/scripts/install-settings.sh | bash
```

Install other configurations:

```sh
npm install --global pure-prompt
brew install zsh-syntax-highlighting
```

And download [Snazzy theme](https://github.com/sindresorhus/iterm2-snazzy#install)
