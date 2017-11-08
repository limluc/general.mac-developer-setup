# general.mac-developer-setup
This is used for general guidelines on setting up mac

Inspired by https://github.com/nicolashery/mac-dev-setup

This can be used for developer/to-be developer with following profiles:
* Java / Scala
* Python
* Node JS

# Homebrew
https://brew.sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile

# iTerms + oh-my-zsh
https://gist.github.com/ZenLulz/c812f70fc86ebdbb189d9fb82f98197e

iTerms
brew cask install iterm2
Oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# Git
brew install git
See other general config

# Atom
brew cask install atom

# Python
brew install python

# Node
brew install node
