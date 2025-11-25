# Molecular Mechanics Computation
> For calculations, we will use Psi4

## Installing the conda and environment
- Right-click and Open in terminal, then at the Command prompt type wsl

``` bash
# Anaconda Installation
cd ~
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
source ~/miniconda3/etc/profile.d/conda.sh 
```
```
 # Setting the Environment
conda create --name <env> --file <this file>
conda activate psiresp
```
- Since we work with wsl, let's install a browser and jupyter for convenience
``` bash
sudo apt-get install firefox
pip install jupyterlab
python -m ipykernel install --user --name psiresp
```
```
jupyter-lab
```
