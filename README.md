# About

Fork of the patched belabox srt + buildfix from tt2468

## Build Instructions

```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install tclsh pkg-config cmake libssl-dev build-essential
git clone https://github.com/thetobby/srt.git
cd srt
./configure
make -j12
```
