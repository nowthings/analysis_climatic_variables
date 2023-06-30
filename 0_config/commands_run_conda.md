## run Anaconda
source ~/.bashrc
conda info
conda activate nowthing
anaconda-navigator

## Install Pytorch
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia

## usage statistics are refreshed every 1 second
watch-n 1 nvidia-smi