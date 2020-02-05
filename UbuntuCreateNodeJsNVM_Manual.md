# Read before executing use at your own risk

### CreateNodeJs.md ~ UbuntuOnly

#Default set to version 13.3.0  
nvm-version="v13.3.0"

### Install curl to latest version
sudo apt-get install curl -y

### Download and install nvm
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash


#Reload system environment 
source ~/.profile     ## Debian based systems 

### Find out the available version of Node.js 
echo "Available Node.js Versions"
nvm ls-remote


### Automate the nvm install  
nvm install $nvm-version

echo "...This was a sample script... "


## #Auto inject and launch script

cp UbuntuCreateNodeJsNVM_Manual.md CreateNodewithNVMlaunch.sh

chmod 700 CreateNodewithNVMlaunch.sh
./CreateNodewithNVMlaunch.sh


# Install NodeJs Manually

## Add Node.js PPA
#Uncomment the line below to select a specific version
#curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
#curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -

### Next instal the package manually
#sudo apt-get install nodejs -y



# To change default version uncommoment next line 
#nvm list

