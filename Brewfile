# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

install maven

install rbenv
install ruby-build

install python
pip install sphinx
pip install sphinxcontrib-fancybox

# Install more recent versions of some OS X tools
install vim --override-system-vi
tap homebrew/dupes
install homebrew/dupes/grep
tap josegonzalez/homebrew-php
install php55

# Install other useful binaries
install ack
install git
install lynx
install node
install pigz
install rename
install tree
install unrar
install wget

tap homebrew/versions
install lua52

tap dinkypumpkin/get_iplayer
install atomicparsley
install rtmpdump
install ffmpeg
install mplayer
install id3lib
install id3v2
install flvstreamer
install get_iplayer

install exiftool
install nmap
install stunnel
install tcpflow

install haskell-platform
cabal update
cabal install pandoc

# Remove outdated versions from the cellar
cleanup
