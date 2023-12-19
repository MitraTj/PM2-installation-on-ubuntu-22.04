# PM2-installation-on-ubuntu-22.04
If you have confused with installation of PM2 on your ubuntu 22.04 you need to go through following commands:

1. sudo apt install npm
2. sudo apt install build-essential
3. npm config set prefix ~/.npm-global
4. export PATH="$HOME/.npm-global/bin:$PATH"
5. npm cache clean --force
6. npm --version
7. node --version
8. sudo npm install pm2 -g --unsafe-perm
