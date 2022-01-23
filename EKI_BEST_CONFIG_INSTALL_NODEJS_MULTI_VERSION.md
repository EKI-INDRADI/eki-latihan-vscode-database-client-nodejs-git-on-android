# INSTALL MULTI DATABASE


```bash
apt-get install build-essential checkinstall 
apt-get install libssl-dev 
curl -o- https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

command -v nvm

nvm ls-remote | grep -i "latest" 
v4.9.1   (Latest LTS: Argon)
        v6.17.1   (Latest LTS: Boron)
        v8.17.0   (Latest LTS: Carbon)
       v10.24.1   (Latest LTS: Dubnium)
       v12.22.9   (Latest LTS: Erbium)
       v14.18.3   (Latest LTS: Fermium)
       v16.13.2   (Latest LTS: Gallium)


nvm install 14.18.3
nvm install 16.13.2


----- which one for set NODEJS & NPM VERSION
nvm use 14.18.3  (nodejs version 14.xx recomended for User NestJs / Angular)
nvm use 16.13.2  (nodejs version 16.xx (latest version) not recomended for User NestJs / Angular, many bug node-gyp , etc)
----- 


exit ubutnu
exit termux
reclose termux

start ubuntu service again
./start-ub<tab> enter

npm --version
node --version

example :

npm I -g nodemon
npm I -g pm2
npm i -g @angular/cli
npm i -g @nestjs/cli

```