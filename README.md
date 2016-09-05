# ubuntu-desktop

#Python3
PACKAGES="
openssh-server 
ttf-mscorefonts-installer 
tmux 
tmuxinator 
screen 
vim-gui-common 
zsh 
make 
build-essential 
libssl-dev 
zlib1g-dev 
libbz2-dev 
libreadline-dev 
libsqlite3-dev 
wget 
curl 
llvm 
libncurses5-dev 
git
"

apt-get install $PACKAGES

sudo systemctl enable ssh
