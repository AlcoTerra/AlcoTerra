# README.md

#Allows selection of Node.js


# Install curl to latest version
sudo apt-get install curl -y

#Reload system environment 
source ~/.profile     ## Debian based systems 


# find out the available version of Node.js 
echo "Available Node.js Versions"
nvm ls-remote


## Add Node.js PPA


#Uncomment the line below to select a specific version
#curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
#curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -



#Install NodeJs
sudo apt-get install nodejs -y


This is a simple script 

# CreateNodeJs.md

#UbuntuOnly

#Auto inject and launch script

cp UbuntuCreateNodeJsNVM_Manual.md CreateNodewithNVMlaunch.sh

chmod 700 CreateNodewithNVMlaunch.sh

./CreateNodewithNVMlaunch.sh

