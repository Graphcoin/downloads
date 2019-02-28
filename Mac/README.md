# For Mac OS X High Sierra+ -

### In Terminal, run the following command:

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Once the package manager has been installed, run this command: 

`brew install boost`

### If the app continues to crash after several "Reopen" attempts:

1. Left-click on the app, and "Show Package Contents"
2. Go to Contents -> MacOS -> "Graphcoin-Qt"

### If you're starting a new wallet:

1. After the intial load attempt, if the wallet crashes on first sync - 
2. Download the "Blocks" and "Chainstate" folders from this directory.
3. In Mac OS X, click on Finder - and select from the top menu Go -> Go To Folder.. -> `/Users/(your_user_name)/Library/application support/GraphcoinCore`
4. Move the Blocks and Chainstate downloads into this folder.
5. Restart Graphcoin-Qt to sync.
