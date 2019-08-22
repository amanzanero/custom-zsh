# custom-oh-my-zsh

My oh-my-zsh customizations

## Pre-requisites:

[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh),
[iterm2](https://www.iterm2.com/)

## Installation:

Clone this repository and replace your .zshrc with this one.

Or, just copy and paste the contents from this .zshrc into your current .zshrc and overwrite it.

If no .zshrc, create a .zshrc in your root dir:

```bash
touch ~/.zshrc
```

## To install plugins:

Copy and paste the following in iterm and run:

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
```
