```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
~/miniconda3/bin/conda init
source ~/.bashrc
conda config --set auto_activate_base false
conda --version
```

```
conda env create -f environment.yaml
conda activate defake
```