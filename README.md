# dotfiles
My personal configuration

#### Init all submodules post clone
git submodule update --init --recursive

#### Updating all plugins (latest)
git submodule update --recursive --remote

#### Install pathogen.vim
cd ~/.vim/bundle && \
git clone https://github.com/tpope/vim-sensible.git

#### Create Symlink to plugin submodules
cd ~/.vim && \
ln -s ~/Dev/dotfiles/vim/plugins bundle
