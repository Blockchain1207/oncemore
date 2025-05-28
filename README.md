# oncemore

# GIT

## clone with token
```sh
git clone https://<PAT>@github.com/username/repo.git
```

## git config & commit
```sh
git config [option --global --local] --list

git config --global user.name "Your Name"
git config --global user.email you@example.com
# After doing this, you may fix the identity used for this commit with:
git commit --amend --reset-author

git status
git add "filename" | -A
git commit -m "[commit message]"


git remote add origin [url]
git push --set-upstream origin master
git push -u origin main

git remote remove origin
git remote set-url origin [url]

git branch [branch name]
git checkout [branch name]	
```

# Cosmos Env
```sh
sudo apt update
sudo apt install golang docker.io jq git cmake gcc make
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
## SEI
rustc version: 1.69.0
```sh
rustup show
rustup install 1.69.0
rustup default


seid keys add [key_name] --recover
```


# NODE & YARN

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

source ~/.bashrc
nvm install [version]

npm install pm2@latest -g

nvm use [version]

npm install --global yarn

rm -rf node_modules
npm install
```

# Hardhat zkSync
```sh
npx zksync-cli create demo --template hardhat_solidity

```


# DOWNLOAD WEBSITE
```sh
npm i -g @yokra/webdumper
webdumper -u https://website.com/ -o /path/to/output/folder
```


# GO

## install gvm
```sh
apt-get install bison
bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
```
## hexdump issue
```sh
apt-get install bsdmainutils
```
## gvm use error
```sh
[[ -s "$GVM_ROOT/scripts/gvm" ]] && source "$GVM_ROOT/scripts/gvm"
```

# Ubuntu

## Execute Permission
```sh
chmod +x the_file_name
```

## Zip
```sh
zip -r [file_name.zip] [files_names]
zip [options] [file_name.zip] [files_names]
zip -r archive_name.zip folder_to_zip/ -x 'folder_to_zip/exclude_directory/*'

unzip [file_name.zip] -d [foler_name]  
```

## PM2
```sh
pm2 resurrect

npm install -g ts-node-dev
npm install -g nodemon pm2
pm2 start "nodemon src/index.ts" --name "supervolume"

pm2 start "ts-node src/index.ts" --name "volume"
pm2 start "ts-node src/index.ts" --name "holder"
pm2 start ecosystem.config.js --env production --interpreter ./node_modules/.bin/ts-node --interpreter-args "--transpile-only"
```

## ufw
```sh
sudo ufw enable
sudo ufw allow 'OpenSSH'
```

# MongoDB
```
mongod --config /etc/mongod.conf
```

```root@m12232:/var/lib# 
ll -l|grep mongo
```
```root@m12232:/var/lib/mongodb#
chown mongodb:mongodb -R *
```

## Net Command
netsh interface ipv4 set subinterface "Ethernet" mtu=1350 store=persistent

0x84C3731CFFcb5734109BD9FdFc5bF2b9Efea56e2
