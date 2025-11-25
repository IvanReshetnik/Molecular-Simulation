# Вычисление параметров молекулярной механики
> Для расчетов будем использовать Psi4

## Установка conda и среды
- Нажмите правую кнопку мыши и Open in terminal, после чего в командной строке введите wsl

``` bash
# Установка anaconda
cd ~
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
source ~/miniconda3/etc/profile.d/conda.sh 
```
```
 # Установка среды
conda create --name <env> --file <this file>
conda activate psiresp
```
- Поскольку работаем с wsl установим браузер и jupyter для удобства
``` bash
sudo apt-get install firefox
pip install jupyterlab
python -m ipykernel install --user --name psiresp
```
