# BPI-tools
------------
tools for Banana Pi

  

How to install from Github:
-----------------------------------------
```
curl -sL https://github.com/BPI-SINOVOIP/bpi-tools/raw/master/bpi-tools | sudo -E bash -
```


EX: bpi-copy
-----------------------------------------
Copy data from SD-Card/EMMC to be Images 
```
sudo bpi-copy < device path> < xxxxx.img.zip>
```

To burn into certain device,please run the following command
```
sudo bpi-copy < xxxxx.img.zip> < device path>
```


EX: bpi-update
-----------------------------------------
update W2 new kernel version 
```
sudo bpi-update -c bpi-w2.conf
```

EX: bpi-bootsel
-----------------------------------------
M3 imgae is switchable to M2_Plus
```
sudo bpi-bootsel /usr/lib/u-boot/bananapi/bpi-m2p/BPI_M2P_720P.img.gz
```

M2_Plus imgae is switchable to M3 imgae
```
sudo bpi-bootsel /usr/lib/u-boot/bananapi/bpi-m3/BPI_M3_720P.img.gz
```
