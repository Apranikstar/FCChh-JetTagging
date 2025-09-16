# Check for Nvidia driver
```bash
nvidia-smi
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
conda create -n weaver python=3.10
conda activate weaver
pip install torch
pip install weaver-core
```
