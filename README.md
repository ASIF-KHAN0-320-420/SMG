a## 🐍 PYTHON 3.11 SETUP

## Agar Termux mein 
## Python 3.13 installed hai
## aur Python 3.11 use karna.
## Chahta ha to ye command 
## termux ma Lagana👇👇👇

```
### 🚀 👇👇copy paste INSTALL PYTHON 3.11

`curl -fsSL https://raw.githubusercontent.com/adybag14-cyber/termux-python/main/install.sh | bash -s -- 3.11`

`python3.11 -m pip install requests`
`python3.11 -m pip install bs4`

### 🔍 CHECK VERSION

`python3.11 --version`

### 🔄 PYTHON 3.13 WAPIS LANA HO
### 🔍 CHECK VERSION
## ⚡ INSTALL TOOL ON TERMUX

`pkg update`
`pkg upgrade`

`pkg install python`
`pkg install git`

`pip install requests`
`pip install bs4`
`pip install futures`
`pip install mechanize`



`rm -rf SMG`
`cd`
`git clone https://github.com/ASIF-KHAN0-320-420/SMG`
`cd SMG`
`python DSD.py`



## Python Cleanup

- `cd ~`
- `pkg uninstall python2 -y`
- `rm -f $PREFIX/bin/python2*`
- `rm -f $PREFIX/bin/python3.10*`
- `rm -f $PREFIX/bin/python3.12*`
- `rm -f $PREFIX/bin/python3.13*`
- `rm -f $PREFIX/bin/pip2*`
- `rm -f $PREFIX/bin/pip3.10*`
- `rm -f $PREFIX/bin/pip3.12*`
- `rm -f $PREFIX/bin/pip3.13*`

## Python 3.12 Reinstallation

- `pkg uninstall python3.12 -y`
- `pkg install python3.12 -y`

## Remove Existing Links

- `rm -f $PREFIX/bin/python $PREFIX/bin/python3 $PREFIX/bin/python-config $PREFIX/bin/python3-config $PREFIX/bin/pip $PREFIX/bin/pip3`

## Create Python Links

- `ln -sf python3.12 $PREFIX/bin/python3`
- `ln -sf python3 $PREFIX/bin/python`
- `ln -sf python3.12-config $PREFIX/bin/python3-config`
- `ln -sf python3.12-config $PREFIX/bin/python-config`

## Create Pip Links

- `ln -sf pip3.12 $PREFIX/bin/pip3`
- `ln -sf pip3 $PREFIX/bin/pip`

## Check Versions

- `python --version`
- `pip --version`
