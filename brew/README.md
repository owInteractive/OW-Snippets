## Brew

Install homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Install gitflow

```
brew install git-flow-avh
```

Install Google Chrome

```
brew cask install google-chrome
```

Install Firefox

```
brew cask install firefox
```

Install Opera

```
brew cask install opera
```

Install Visual Studio Code

```
brew cask install visual-studio-code
```

Install Sequel Pro

```
brew cask install sequel-pro
```

Install Docker

```
brew cask install docker
```

Install Captain

```
brew cask install captain
```

Install Iterm2

```
brew cask install iterm2
```

Install Slack

```
brew cask install slack
```

Install SourceTree

```
brew cask install sourcetree
```

Install Spotify

```
brew cask install spotify
```

Install Postman

```
brew cask install postman
```

Install Java

```
brew cask install java
```

Install Node

```
brew install node
```

Install Redis

```
brew install redis
ln -sfv /usr/local/opt/redis/*.plist ~/Library/LaunchAgents
redis-cli ping
```

Install Cask Upgrade

```
brew tap buo/cask-upgrade
```

Update, Upgrade and Cleanup *Brew*

```
brew update && brew upgrade && brew cleanup
```

Update, Upgrade and Cleanup *Brew* and Upgrade progams installed on *Brew* Cask after all

```
brew update && brew upgrade && brew cleanup && brew cu --all --cleanup --yes
```

### Useful links
[Brew Cask Upgrade](https://github.com/buo/homebrew-cask-upgrade)