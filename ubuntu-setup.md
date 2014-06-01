# Use Mojo with Ubuntu

Latest LTS release: 14.04, Trusty Tahr

http://xubuntu.org/getxubuntu/

Download with uTorrent

## Enable sshd

sudo apt-get install openssh-server
sudo restart ssh

## VirtualBox only
### Install VBox Guest Additions

sudo apt-get update
sudo apt-get upgrade
sudo apt-get install dkms


## Install Chrome

wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" \
    >> /etc/apt/sources.list.d/google-chrome.list'

sudo apt-get update
sudo apt-get install google-chrome-stable

## Install Arduino

VirtualBox: USB device in use by someone else ...

http://stackoverflow.com/questions/14689354

