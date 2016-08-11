# Laptop Builder

The Faria Systems Laptop Builder is a single script which should be executed after an OS X installation has been provisioned on a laptop or desktop, intended for developer use.

The Laptop Builder automatically pre-installs common application dependencies, build tools, development utilities and desktop applications that are either required or highly recommended by senior staff.

This script can be run with:

    curl --remote-name https://raw.githubusercontent.com/eduvo/laptop/master/mac
    sh mac 2>&1 | tee ~/laptop.log


MG changes:

1. added Oh My Zsh
2. Removed brew hub
3. Additional homebrew packages:
direnv
erlang
elixir
gitup
most
puma-dev
sqlite
node
4. Remove check for rbenv (was choking with rbenv already installed)
5. Don't install GH UI, atom, teamviewer, textmate, textwrangler, virtualbox
6. remove color settings
7. Add phoenix + related bits
8. Add gitx
9. downgrade mysql to 5.5
