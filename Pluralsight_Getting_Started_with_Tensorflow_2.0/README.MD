# Pluralsight - Getting Started With TensoFlow 2.0

Formation Pluralsight https://app.pluralsight.com/library/courses/getting-started-tensorflow-20

## Pour commencer


### Pré-requis

Verifier https://pip.pypa.io/warnings/enable-long-paths
```
Powershell As Adminstrator 

New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" `
-Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force
```


### Installation

Dans une fenêtre conda:

```
conda create -n Pluralsight_Getting_Started_with_Tensorflow_2.0_Env python=3.7.6
conda activate Pluralsight_Getting_Started_with_Tensorflow_2.0_Env 
conda install -n Pluralsight_Getting_Started_with_Tensorflow_2.0_Env ipykernel --update-deps --force-reinstall

python -m pip install --upgrade pip

pip3 install pandas
pip3 install matplotlib
pip3 install seaborn
pip3 install scikit-learn
pip3 install tensorflow

```

## Démarrage


