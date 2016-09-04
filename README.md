*NOTE: THIS BRANCH CUSTOMIZED FOR MIKE G, MAY NOT BE APPROPRIATE FOR EVERYONE*)

# Laptop Builder

The Faria Systems Laptop Builder is a single script which should be executed after an OS X installation has been provisioned on a laptop or desktop, intended for developer use.

The Laptop Builder automatically pre-installs common application dependencies, build tools, development utilities and desktop applications that are either required or highly recommended by senior staff.

This script can be run with:

    curl --remote-name https://raw.githubusercontent.com/eduvo/laptop/mike_g/mac
    sh mac 2>&1 | tee ~/laptop.log


MG changes:

1. added Oh My Zsh
2. Removed brew hub
3. Additional homebrew packages:
direnv
erlang
elixir
gitup
go
most
prince
puma-dev
rabbitmq
sqlite
node
4. Remove check for rbenv (was choking with rbenv already installed)
5. Don't install GH UI, atom, teamviewer, textmate, textwrangler, virtualbox
6. remove color settings
7. Add phoenix + related bits
8. Add gitx
9. Add iterm2
10. Show hidden files by default
11. Add Alfred, Evernote, ST3, Navicat Premium
12. Add Firefox Developer Edition
