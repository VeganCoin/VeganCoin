
VeganCoin SHA256
25,000,000 coins
Block Rewaard = 25 coins
Halving 200,000 blocks
rpc = 22116
port = 22117

________________

Sample VeganCoin.conf

rpcuser=VeganCoinrpc
rpcrpcpassword=2596a6a36d42416b5486386c
rpcallowip=127.0.0.1
rpcport=22116
port=22117
daemon=1
server=1
gen=0
addnode=104.131.234.129

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

Sample VeganCoin.conf for daemon

daemon=1
rpcuser=VeganCoinrpc
rpcrpcpassword=2596a6a36d42416b5486386c









