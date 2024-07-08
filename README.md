#PFIA 2024

## Open with colab

AAW: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mileem/PFIA_2024/blob/main/src/fatigue_material_AAW.ipynb)

## Prerequities
### Install miniconda

### Windows
```shell
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o miniconda.exe
start /wait "" miniconda.exe /S
del miniconda.exe
```

### Linux
```shell
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

### MacOS
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install --cask miniconda
```


## Installation


```shell
conda create --name pfia_2024 --file requirements.txt 
conda install jupyter
ipython kernel install --name pfia_2024 --user
```

Ou

```shell
conda create --name pfia_2024 pandas numpy matplotlib seaborn scikit-learn tensorflow=2.15 tensorflow-probability jupyter
ipython kernel install --name pfia_2024 --user
```


## Run

```shell
juptyer notebook
```