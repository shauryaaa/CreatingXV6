# CreatingXV6
how to download XV6 on a windows system




# STEP 1: 
```
install ubuntu on windows using microsoft store
```
# STEP 2: 
```
set User and password on the ubuntu terminal 
```

# STEP 3:
```
open Ubuntu and install basic libraries and packages which will be needed
sudo add-apt-repository main
sudo add-apt-repository universe
sudo add-apt-repository restricted
sudo add-apt-repository multiverse
sudo apt-get install gcc
sudo apt-get install build-essential
sudo apt install git
```
 
# afterwards do the following things:
```
sudo apt-get install qemu
sudo apt-get install libc6:i386
git clone https://github.com/mit-pdos/xv6-public.git xv6
chmod 700 -R xv6
cd xv6
make
make qemu
```
please star this repo!!!
