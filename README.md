VeganCoin SHA256

25,000,000 coins 25,000,000

Block Rewaard = 25 coins

Halving 200,000 blocks

________________

Sample VeganCoin.conf

rpcuser=Yourname

rpcrpcpassword=Yourpassword

rpcallowip=127.0.0.1

rpcport=22116

port=22117

addnode=104.131.234.129

addnode=188.226.162.76

addnode=54.186.136.108

_______________

Compile QT for Linux (Ubuntu & Fedora)

sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.1-dev libdb5.1++-dev qt-sdk make

qmake -qt=qt4 "USE_UPNP=-"

make

________________

Compile daemon (VeganCoind)

sudo apt-get update

sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.1-dev libdb5.1++-dev make

(navigate to VeganCoin/src)

make -f makefile.unix

________________

If compile fails

sudo apt-get install git build-essential libssl-dev libboost-all-dev libdb++-dev libminiupnpc-dev qt-sdk -y

________________

Sample VeganCoin.conf for daemon

daemon=1

rpcuser=VeganCoinrpc

rpcrpcpassword=2596a6a36d42416b5486386c



