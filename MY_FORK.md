## Torchvision
### WHY:
I am createing this fork after some frustration with installing Pytorch while playing around with ML project DeOldify
### Requirements:
* ROCm 
* Pytorch

### Install 
Note: Do not use pip. This will use torchvision CPU

Download source:

    git clone https://github.com/pytorch/vision.git
    
Execute setup.py:

    sudo python3 setup.py install

### Test:

import torchvision
torchvision.__version__
<!--stackedit_data:
eyJoaXN0b3J5IjpbODg0MTg4MjQ1XX0=
-->