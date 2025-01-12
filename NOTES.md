# Notes for YeyLearningRuby
Created new folder:
cd ~/Documents
mkdir yeylearningruby
cd yeylearningruby

Installed Git:
sudo apt update
sudo apt install git
configured git with my user information
git config --global user.name geekyyey
git config --global user.email geekyyey@gmail.com



Installed Ruby:
sudo apt update
sudo apt install ruby-full
verified its version: ruby-v

Installed Visual Studio:
sudo apt update
sudo apt install software-properties-common apt-transport-https wget -y

with the help of ChatGPT: 
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg

sudo install -o root -g root -m 644 packages.microsoft.gpg /usr/share/keyrings/rm packages.microsoft.gpg

added VS code repository: echo "deb [arch=amd64 signed-by=/usr/share/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" | sudo tee /etc/apt/sources.list.d/vscode.list

updated package: sudo apt update
installed VS: sudo apt install code

Added Ruby extensions in VS Code
Added Ruby Solargraph
Ruby Test Explorer
configured VS Code for Ruby
Ruby Path: /usr/bin/ruby

The website HTML files are hosted in https://github.com/geekyyey/Learning-HTML5, cloned the repository 
