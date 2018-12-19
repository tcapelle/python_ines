#!/bin/bash
pip install pillow==4.1.1 --upgrade

sed -n -e '/^tmpfs \/dev\/shm tmpfs defaults,size=/!p' -e '$atmpfs \/dev\/shm tmpfs defaults,size=1g 0 0' -i /etc/fstab
mount -o remount /dev/shm

mkdir -p /root/.torch/models
mkdir -p /root/.fastai/data
ln -s /root/.torch/models /content
ln -s /root/.fastai/data /content
rm -rf /content/sample_data/

pip install fastai --upgrade
