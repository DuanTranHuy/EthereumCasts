# EthereumCasts
Install Meta Mask extension and back up mnemonic phrases

Create an infura account you will receive email with content like this:

Main Ethereum Network
https://mainnet.infura.io/80TKZpSSBLW5cSaIWoK1 

Test Ethereum Network (Ropsten)
https://ropsten.infura.io/80TKZpSSBLW5cSaIWoK1 

Test Ethereum Network (Rinkeby)
https://rinkeby.infura.io/80TKZpSSBLW5cSaIWoK1 

Test Ethereum Network (Kovan)
https://kovan.infura.io/80TKZpSSBLW5cSaIWoK1 

IPFS Gateway
https://ipfs.infura.io 

IPFS RPC
https://ipfs.infura.io:5001 

Window: 

Note: Open cmd or Powershell as admin

- install node-gyp: npm install -g node-gyp 

- download and install build tools manually https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2017

- install Python 2.7

- register msvs-version to npm: 
  npm config set msvs_version 2015 (if running 2015 build tool)
  npm config set msvs_version 2017 (if running visual 2017  build tool)

- register python-executable to npm:
  npm config set python python\path\to\executable  (Note: The path should point directly to python.exe)
  EX: npm config set python C:\Python27\python.exe

- Then open source code location
  npm install
  npm install --save-dev web3@1.0.0-beta.26  

Linux base OS / Mac OSX:

- Open source code location
  npm install
  npm install --save-dev web3@1.0.0-beta.26  
