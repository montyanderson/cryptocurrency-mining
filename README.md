# cryptocurrency-mining

## Compiling cpuminer-multi

```
sudo apt-get install gcc make automake libcurl4-openssl-dev libjansson-dev &&
wget https://github.com/lucasjones/cpuminer-multi/archive/v1.0.3.zip &&
unzip v1.0.3.zip &&
cd cpuminer-multi-1.0.3/ &&
./autogen.sh &&
./configure CFLAGS="-march=native" &&
make
```
