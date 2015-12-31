# Laptop Builder

The Faria Systems Laptop Builder is a single script which should be executed after an OS X installation has been provisioned on a laptop or desktop, intended for developer use.

The Laptop Builder automatically pre-installs common application dependencies, build tools, development utilities and desktop applications that are either required or highly recommended by senior staff.

This script can be run with:

    curl --remote-name https://raw.githubusercontent.com/eduvo/laptop/master/mac
    sh mac 2>&1 | tee ~/laptop.log
