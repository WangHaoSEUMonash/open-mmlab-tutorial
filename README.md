# SenseTime bilibili homepage
[SenseTime](https://space.bilibili.com/630319191)

# open-mmclassification-tutorial
suzhou-server
*The tutorial is summarized by the [open course](https://www.bilibili.com/video/BV1Lh411S7VY) of SenseTime*


**Create a virtual environment**

conda create -n open-mmclassification python=3.7 -y

**Install a proper PyTorch**

conda install pytorch==1.8.0 torchvision==0.9.0 torchaudio==0.8.0 cudatoolkit=10.2 -c pytorch

**Install [MMCV](https://github.com/open-mmlab/mmcv)**

In this server: pip install mmcv-full -f https://download.openmmlab.com/mmcv/dist/cu102/torch1.8.0/index.html

**Install [mmclassification](https://github.com/open-mmlab/mmclassification)**

The more useful one is its [doc](https://mmclassification.readthedocs.io/en/latest/)
