#  ZSH

### Installation Zsh

```
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

### Alias

```
alias nibi="npm install && bower install"
alias sassw="sass -w sass:css"
alias zshc="~/.zshrc"
alias mg="mongod"
alias rs="redis-server"
alias pyserver="python -m SimpleHTTPServer"
```

#### Mac Helpers
```
alias show_file="defaults write com.apple.Finder AppleShowAllFiles YES && killall Finder"
alias hide_file="defaults write com.apple.Finder AppleShowAllFiles NO && killall Finder"
```

### Plugins
```
plugins=( [plugins...] git sublime zsh-syntax-highlighting yeoman web-search)
```

#### Zsh-syntax-highlighting

by [zsh-users/zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

#### Yeoman plugin ZSH

by [edouard-lopez/yeoman-zsh-plugin](https://github.com/edouard-lopez/yeoman-zsh-plugin/blob/master/readme.md)

