Compiled wallets / daemon for download

Wallets available for Mac OSX 10.10+, Windows 8+, Ubuntu 16.04
Compiled daemon also available for Ubuntu 16.04

See the wiki for setup guides

## For a faster wallet sync - Add Nodes

1. Click in the wallet menu "Tools -> Open Wallet Configuration File"

2.Copy and paste the following data into the notepad -

banscore=10000
bantime=60

## And your add nodes can be found here:

https://explorer.graphcoin.net/connections
=======
1.  Click in the wallet menu "Tools -> Open Wallet Configuration File"
2.  Copy and paste the addnode= data into the notepad.
3.  Save the file, and restart wallet

# For Mac OS X High Sierra -

### In Terminal, run the following command:

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Once the package manager has been installed, run this command: 

`brew install boost`
