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
2.  Copy and paste the following data into the notepad -


addnode=199.247.27.78:22629
addnode=185.162.251.192:22629
addnode=95.179.141.91:22629
addnode=94.16.121.144:22629
addnode=37.221.193.200:22629
addnode=95.216.81.34:22629
addnode=80.211.60.189:22629
addnode=142.93.125.230:22629
addnode=168.62.38.187:22629
addnode=138.197.163.226:22629
addnode=54.39.96.184:22629
addnode=104.156.254.141:22629
addnode=144.202.69.213:22629
addnode=207.246.98.90:22629
addnode=149.28.75.41:22629
addnode=173.199.126.21:22629

3.  Save the file, and restart wallet

# For Mac OS X High Sierra -

### In Terminal, run the following command:

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Once the package manager has been installed, run this command: 

`brew install boost`
