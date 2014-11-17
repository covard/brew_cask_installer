brew_cask_installer
===================

Repo to keep my brew cask installer script

Install Homebrew

`$ ruby -e "$(curl -fsSL "https://raw.githubusercontent.com/Homebrew/install/master/install")"`

Setup Cask

`$ brew tap caskroom/cask`
`$ brew install caskroom/cask/brew-cask`

after installing alfred need to run this to link them

`$ brew cask alfred link`


Searching for casks (this will find alfred, duh ;-) )

`$ brew cask search alfred`
