# c3d-cat-movement-recognition-pytorch
This repo is the graduation project for Ha Young Jang, Eun Hee Ham and Sung Yoon Ahn
It is done by using the C3D model

<b>Installation</b>
<hr>
The code was tested with Anaconda and Python 3.6

To install anaconda go to https://docs.anaconda.com/anaconda/install/ and follow the installation guidelines
1) Clone repo or download zip
2) Install pytorch from https://pytorch.org/
3) You can configure your dataset and pretrained model in mypath.py
4) To train the model run 
  python train.py
   in anaconda</br>
<b>Personal dataset</b>
 You can add your own video dataset by putting your classified videos in file UCF-101
 When using your own dataset please change the appropriate lines in train.py and dataloaders/ucf_labels.txt
<b>Demo</b>
The demo video can be made by running
python inference.py
appropriate changes are needed in the code
