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
build-essential
autoconf
libtool
pkg-config
python-opengl 
python-imaging 
python-pyrex
python-pyside.qtopengl 
idle-python2.7
qt4-dev-tools
qt4-designer 
libqtgui4
libqtcore4 
libqt4-xml
libqt4-test 
libqt4-script
libqt4-network 
libqt4-dbus
python-qt4
python-qt4-gl
libgle3 
python-dev
python3-dev
libxml2-dev
libxslt1-dev
"

apt-get install $PACKAGES

sudo systemctl enable ssh
