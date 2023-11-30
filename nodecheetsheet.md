first : update
```
sudo apt-get update
```
check if node is install
```
node -v
```

#install
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```
now choose your node version, here it's 16
```
nvm install 16
```



Install NPM and PNPM

    sudo apt install npm
    npm install -g pnpm


source :
[https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm)

<!-- ##Uninstall NodeJS from Ubuntu

If you wish to uninstall NodeJS from your Ubuntu system, run the command below.
```
sudo apt-get remove nodejs
```
The command will remove the package but retain the configuration files. To remove both the package and the configuration files run:
```
sudo apt-get purge nodejs
```
As a final step, you can run the command below to remove any unused files and free up the disk space
```
sudo apt-get autoremove
```
Great! We have successfully installed and tested the installation of NodeJS. We also learned how to uninstall NodeJS from Ubuntu and clean up space. -->