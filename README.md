# zsh-themes
Fork of amuse theme of oh-my-zsh

## Installation
```
sh
git clone https://github.com/5m0k3r/zsh-themes.git
cp PATH/TO/halil.zsh-theme $ZSH/themes/.
```
Then set the theme in your `.zshrc`:

```sh
ZSH_THEME="halil"
```
### To use all the fonts, install Powerline in your system

## Halil Theme Preview:
![](zsh-theme-halil-thumb.gif)

### To Upgrade Oh-My-zsh
Go to root folder of Oh-My-zsh 
```
cd ~/.oh-my-zsh/
```
Stack the halil theme 
```
git stash
```
Upgrade Oh-My-zsh
```
bash tools/upgrade.sh
```
Then, return halil theme
```
git stash pop
```
Enjoy!
