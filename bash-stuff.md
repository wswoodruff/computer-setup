### Good Stuff to include in .bash_profile or .bashrc

```bash
# Lets you type a directory and move to it without needing to prepend with `cd `
shopt -s autocd

# List dirs including hidden files and all perms info
alias la="ls -al"

# Disable automatic visual mode on mouse click for a server
# Grabbed from https://gist.github.com/u0d7i/01f78999feff1e2a8361
# To disable vim automatic visual mode on mouse select,
# add to ~/.vimrc

source $VIMRUNTIME/defaults.vim
set mouse-=a
```
