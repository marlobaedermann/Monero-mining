# Monero-mining
Wie man ein Gerät miningfähig macht.

sudo apt update

sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y

git clone https://github.com/xmrig/xmrig.git

cd xmrig
mkdir build
cd build
cmake

make

./xmrig -o gulf.moneroocean.stream:10128 -u [Walletadresse] -p [NamedesMiners]
