# To run nn example on ARM Cortex M4
* Install caffe
* Do not forget to install the pre-requisites 
```
http://caffe.berkeleyvision.org/installation.html#prerequisites
```
For Ubuntu>17.4 only:
```
# add openblas
sudo apt-get install libopenblas-dev

# Add multiverse in source.list
echo 'deb http://archive.ubuntu.com/ubuntu trusty main restricted universe multiverse' >>/tmp/multiverse.list
sudo cp /tmp/multiverse.list /etc/apt/sources.list.d/
rm /tmp/multiverse.list

# Add boost
sudo apt-get install libboost-all-dev

# Install Caffe
sudo apt install caffe-cpu
```

For Ubuntu14 
```
https://gist.github.com/arundasan91/b432cb011d1c45b65222d0fac5f9232c
```

* Follow the links:
```
https://github.com/ARM-software/ML-examples/blob/master/cmsisnn-cifar10/README.md
https://github.com/ARM-software/CMSIS_5
```

