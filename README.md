# SparTen-Eval

Evaluation on nvidia sparsity training

## TODO

1. [ ] Install necessary package to enable sparsity training
   1. [ ] `APEX` from Nvidia
      1. Need `python3-dev`
2. [ ] Create pytorch model and download dataset for evaluation
   1. [ ] AlexNet
   2. [ ] Cifar

## Installation scripts used

1. PyTorch

   pip install torch==1.7.1+cu101 torchvision==0.8.2+cu101 torchaudio==0.7.2 -f https://download.pytorch.org/whl/torch_stable.html

2. Apex lib

   git clone https://github.com/NVIDIA/apex
   cd apex
   pip install -v --disable-pip-version-check --no-cache-dir --global-option="--cpp_ext" --global-option="--cuda_ext" ./
