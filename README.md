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

./xmrig -o gulf.moneroocean.stream:10128 -u [Walletadresse(44t42kr2Zd3CUKuWszi1A3GxLtfZpm39NexjE4wBdM8YTaHL5mTJYxf1R9bfyvLZwLirCfDTTZ2oXWwuhrxxn86a2vVGNun)] -p [NamedesMiners]
