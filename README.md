# general.mac-developer-setup
This is used for general guidelines on setting up mac

Inspired by 
https://github.com/nicolashery/mac-dev-setup
https://github.com/monfresh/laptop
http://sourabhbajaj.com/mac-setup/Homebrew/Usage.html

This can be used for developer/to-be developer with following profiles:
* Java / Scala
* Python
* Node JS

# Cloud
Get OneDrive, GDrive, and Dropbox

brew cask install
    dropbox \
    google-chrome \
    google-drive-file-stream

# Other Useful App

brew cask install
    alfred \
    appcleaner \
    caffeine \
    cheatsheet \
    docker \
    doubletwist \
    google-hangouts \
    flux \
    1password \
    spectacle \
    sublime-text \
    superduper \
    totalfinder \
    transmission \
    valentina-studio \
    vlc
    
# Virtual Env
brew cask install virtualbox vagrant vagrant-manager

# Install XCode
App Store

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
plugins=(git colored-man colorize github jira vagrant virtualenv pip python brew osx zsh-syntax-highlighting)

# Git
brew install git
See other general config

# Atom
brew cask install atom

# Python
brew install python

# Node
brew install node

# Ruby via RVM
curl -L https://get.rvm.io | bash -s stable --ruby

# Java

Latest Java
brew cask install java

brew install jenv

brew tap caskroom/versions
brew cask install java8

IDE
brew cask install caskroom/cask/intellij-idea-ce

# Other DB Tool

MongoDB/NoSQL
brew update
brew install mongo

Redis
brew update
brew install redis

# Deployment Tool

Heroku
brew install heroku-toolbelt
heroku update

Docker
brew install docker docker-compose docker-machine xhyve docker-machine-driver-xhyve
sudo chown root:wheel $(brew --prefix)/opt/docker-machine-driver-xhyve/bin/docker-machine-driver-xhyve
sudo chmod u+s $(brew --prefix)/opt/docker-machine-driver-xhyve/bin/docker-machine-driver-xhyve

Credit to:
https://pilsniak.com/how-to-install-docker-on-mac-os-using-brew/

# Other Cool Tools

ElasticSearch
brew install elasticsearch
