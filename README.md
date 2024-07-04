# Sonaric
in this guide you will learn how to set up Sonaric node and eran points.

Sonaric on X(https://x.com/SonaricNetwork)

# OS requirement
Sonaric AI Node is supported on the following Linux distributions:

Ubuntu 22.04+
Debian 12+
Fedora 40+
CentOS 8+
Rocky Linux 8+

# install dependencies
```
sudo apt-get update && sudo apt-get upgrade -y
```
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
nvm install 20
nvm use 20
npm install -g npm@latest
```
# install Sonaric node
Run the following command to download and execute the installation script:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/monk-io/sonaric-install/main/linux-install-sonaric.sh)"
```
The script will install Sonaric and its dependencies. This process may take a few minutes.

Once the installation is complete, sonaricd will be started automatically.

You can access the Sonaric GUI by opening a web browser and navigating to http://localhost:44004

![sonaric01](https://github.com/Theshaho/Sonaric/assets/25084190/f5966033-e009-4f5d-a729-8a70fa81b27c)

# Edit node name
The node-rename command allows you to rename your node. This command is useful for changing the name of your node.
```
sonaric node-rename -n YOUR_NAME
```
# see your node info
following commands shows you node info
```
sonaric node-info
```
![Screenshot 2024-07-04 124648](https://github.com/Theshaho/Sonaric/assets/25084190/9cb5cf79-a50d-4582-b3a2-69c2256ba3ac)

# see your points
```
sonaric points
```
![Screenshot 2024-07-04 124756](https://github.com/Theshaho/Sonaric/assets/25084190/bd7df654-5ec3-423a-b706-3380f5dddceb)

# check your rank
use  Sonaric Tracker to see your node and server info
```
https://tracker.sonaric.xyz/
```
![Screenshot 2024-07-04 124842](https://github.com/Theshaho/Sonaric/assets/25084190/154ff003-04ba-4acb-a52a-51500cecd96d)

# About me

