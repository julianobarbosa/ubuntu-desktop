# ubuntu-desktop

#Python3
PACKAGES="
exuberant-ctags
ncurses-term
python-jinja2 
curl
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
