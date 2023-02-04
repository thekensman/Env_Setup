# ZSH Syntax Highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc

# ZSH Substring Search
git clone https://github.com/zsh-users/zsh-history-substring-search

Note you'll need to install vim since vi comes by default
sudo apt install vim
