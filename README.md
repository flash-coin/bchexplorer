BCH Explorer
=======

## Setup BCH Blockchain Explorer API 

## 1. Setup Enviroment:
You need a Ubuntu 16.04 to run Blockchain Explorer API
Install Zeromq version 4.2.2 by following the instruction:
(https://gist.github.com/katopz/8b766a5cb0ca96c816658e9407e83d00)
Install NVM: 
(wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash)
Install Nodejs version: v4.8.7: nvm install v4.8.7
Install PM2: npm install pm2 -g

## 2. Setup Blockchain Explorer API
    1. Clone the bchexplorer to your machine
```bash
$ git clone git@github.com:flash-coin/bchexplorer.git
```
    2. Untar bchexplorer.tar.gz

```bash
$ cd bchexplorer
$ untar -xvzf bchexplorer.tar.gz
```

## 3. Start Blockchain Explorer API
Go to bchexplorer folder:

```bash
$ cd bchexplorer
$ pm2 start bin/bitcored
```

You can then view the BCH coin block explorer at the default location: http://localhost:3001/, and your configuration file will be found in your home directory at ~/.bitcore
System will take some time to synchronize all bitcoin cash blockchain data.

----
