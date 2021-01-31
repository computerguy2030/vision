## Torchvision
### WHY:
I am creating this fork after some frustration with installing Pytorch while playing around with Machine Learning (ML) project [DeOldify](https://github.com/jantic/DeOldify) which I highly recommend if you are interested in getting started in AI, Deep Learning and ML

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
eyJoaXN0b3J5IjpbMjEyODE0NDEyXX0=
-->