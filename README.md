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

   Visit the Nerd Fonts (https://www.nerdfonts.com/font-downloads) website and choose/search a font such as “FiraMono Nerd Font“.

3. Starship prompt
# install starship
brew install starship

# code ~/.zshrc

eval "$(starship init zsh)"

# example ~/.config/starship.toml

mkdir -p ~/.config && starship preset gruvbox-rainbow -o ~/.config/starship.toml

4. Terminal colour scheme
Solarized Dark 

5. Syntax highlighting
# download syntax highlighting extension
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

6. Auto-completion

# install autocompletions extension
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
# update plugins in your ~/.zshrc file
plugins=(
    zsh-syntax-highlighting 
    zsh-autosuggestions
)

7. Configuring Plugins
Next, enable these plugins in your .zshrc file.

Open the .zshrc file in a text editor.
Find the plugins array and add zsh-syntax-highlighting and zsh-autosuggestions
Save the file and restart your terminal or run source ~/.zshrc.
plugins=(git zsh-syntax-highlighting zsh-autosuggestions)

8. Tmux

brew install tmux

9.  Install Fig for autocompletion

brew install fig

