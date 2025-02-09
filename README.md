# Stuff

## Local Machine
#Install brew 
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install iterm2
1. oh-my-zsh
< # install oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
>

2. Nerd-Font

# install 'hack' font using Homebrew
```
curl -sS https://webi.sh/nerdfont | sh; \
source ~/.config/envman/PATH.env
```

3. Starship prompt
# install starship
brew install starship

# code ~/.zshrc

eval "$(starship init zsh)"

# example ~/.config/starship.toml

add_newline = false

[python]
format = 'via [${symbol}${pyenv_prefix}(${version} )(\($virtualenv\) )]($style)'


4. Terminal colour scheme
Solarized Dark 

5. Syntax highlighting
# download syntax highlighting extension
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# add syntax highlighting to the list of plugins in your ~/.zshrc file
plugins=(zsh-syntax-highlighting)


6. Auto-completion

# install autocompletions extension
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
# update plugins in your ~/.zshrc file
plugins=(
    zsh-syntax-highlighting 
    zsh-autosuggestions
)


7. Tmux

brew install tmux

8.  Install Fig for autocompletion

brew install fig

