# Check for Nvidia driver
```bash
nvidia-smi
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
#make sure that it is installed in your work directory:
#/afs/cern.ch/user/work/m/mmalekho/miniconda3

conda create -n weaver python=3.10
conda activate weaver
pip install torch
pip install weaver-core
```
