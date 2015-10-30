# Ruby-Basics
Tutorial on programming basic Ruby scripts

Getting Started


##Installation:
  Installing Ruby is fairly straightforward on Linux, but slightly more complicated on OSX and Windows. 
##Ubuntu
* Open up the terminal and type 
  <pre>sudo apt-get install ruby-full </pre>

##OSX
1. Basic Information
  * Ruby comes pre-installed on OSX, but it's not necessarily the most current version. 
  * You can update to the most current version using [rvm](https://rvm.io/).

2. Make sure **Homebrew** is installed.  
  * We need **brew** in order to download ruby and several other important essentials via the command line. We are able to use the following script to install brew and learn what it's adding:
    <pre>ruby -e “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)”</pre>
  * Press ENTER and enter your password to allow the install
  * To ensure everything worked, type the following:
    <pre>brew doctor</pre>
  * Once you’ve installed Homebrew, insert the Homebrew directory at the top of your PATH environment variable. You can do this by adding the following line at the bottom of your *~/.profile* file
    <pre>export PATH=/usr/local/bin:/usr/local/sbin:$PATH</pre>
  * You may also install **Homebrew Cask**[2], which allows for downloading larger OS X applications and binaries, but we won't need it for this project. You can install via the command line with this command:
    <pre>brew install caskroom/cask/brew-cask</pre>

##Windows
1. Download the latest version of the ruby installer [here](http://rubyinstaller.org/downloads/).
2. Cask by Homebrew : http://caskroom.io/
  
