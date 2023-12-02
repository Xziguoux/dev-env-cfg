# dev-env-cfg
custom develop environment config

# tools install
install zsh and config

```sehll
sudo apt install zsh
chsh -s /bin/zsh
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh
# install pwoerlevel9k
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
```
## plugin
install zsh-autosuggestions, syntax-highlight
```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
# install z.lua
# please download z.lua first
# reminder: not the dir z.lua, it's the command z.lua
eval "$(lua /path/to/z.lua --init zsh enhanced once echo)"
```

