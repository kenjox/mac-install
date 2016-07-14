### Apps
- Chrome https://www.google.se/chrome/browser/desktop/
- iTerm2 https://www.iterm2.com/
- Oh My Zsh 
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
- Brew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
- 1 Password https://1password.com/
- Dropbox https://www.dropbox.com/downloading
- Shortcat https://shortcatapp.com/
- Spectacle https://www.spectacleapp.com/
- Node.Js https://nodejs.org/en/
- Gulp
```
sudo npm install -g gulp
```
- CSS Lint
```
sudo npm install -g csslint
```
- SCSS Lint
```
sudo gem install scss_lint
```
- SASS Lint
```
sudo npm install -g sass-lint
```

### Settings
PNG as standard screenshot format:
```
defaults write com.apple.screencapture type png;killall SystemUIServer
```

Set Git email
```
git config --global user.email "your_email@example.com"
```

Set Git push.default to simple
```
git config --global push.default simple
```

### Generate SSH-key
```
ssh-keygen -t rsa -b 4096 -C "Kommentar på nyckel" && ssh-add ~/.ssh/id_rsa && pbcopy < ~/.ssh/id_rsa.pub
```

### Sublime
- Sublime Text https://www.sublimetext.com/



Add shortcut to Sublime
```
sudo mkdir -p /usr/local/bin && sudo ln -sv "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
```
- Sublime Package Control https://packagecontrol.io/installation
- Sublime Packages (Advanced Install Package)
 -  Emmet,
    Emmet Css Snippets,
    GitGutter-Edge,
    GitSavvy,
    InsertDate,
    Markdown Preview,
    Material Theme,
    SideBarEnhancements,
    Smarty,
    SublimeLinter-contrib-sass-lint,
    SublimeLinter-contrib-scss-lint,
    SublimeLinter-csslint,
    SublimeLinter-php,
