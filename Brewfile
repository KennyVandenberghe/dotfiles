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
install bash-completion

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
tap homebrew/dupes
install homebrew/dupes/grep
tap josegonzalez/homebrew-php
install php55

# This formula didn’t work well last time I tried it:
#install homebrew/dupes/screen

# Install other useful binaries
install ack
install git
install git-extras
install lynx
install tree
install node
install ruby

# Remove outdated versions from the cellar
cleanup
