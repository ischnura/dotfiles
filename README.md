Installation

    git clone git://github.com/ischnura/dotfiles.git

Install vundle vim plugin to download the rest of the plugins

    git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

Then on vim run
    :BundleUpdate :BundleInstall

Inside of ~/.vim make /tmp, inside of which mkdir swap backup undo
    mkdir ~/.vim/tmp ~/.vim/tmp/swap ~/.vim/tmp/undo ~/.vim/tmp/backup

install ctags, ack, ag
    sudo packer -S silver-searcher-git ack ctags
    sudo apt-get install ack-grep

install zsh mc
    sudo apt-get install mc zsh

make zsh default shell
    chsh -s /bin/zsh

start and attach to tmux
    tmux new -s work
    tmux attach -f work
