## 🐍 PYTHON 3.11 SETUP

Agar Termux mein Python 3.13 installed hai aur Python 3.11 use karna chahte hain, to ye commands lagayein 👇👇👇

### 🚀 INSTALL PYTHON 3.11

- `curl -fsSL https://raw.githubusercontent.com/adybag14-cyber/termux-python/main/install.sh | bash -s -- 3.11`

### 📦 INSTALL REQUIREMENTS

- `python3.11 -m pip install requests`
- `python3.11 -m pip install bs4`

### 🔍 CHECK VERSION

- `python3.11 --version`


- `pkg update`
- `pkg upgrade`

- `pkg install python`
- `pkg install git`

- `pip install requests`
- `pip install bs4`
- `pip install futures`
- `pip install mechanize`


- `rm -rf SMG`
- `cd`
- `git clone https://github.com/ASIF-KHAN0-320-420/SMG`
- `cd SMG`
- `python DSD.py`

## 🧹 PYTHON CLEANUP

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

## 🐍 PYTHON 3.12 REINSTALLATION

- `pkg uninstall python3.12 -y`
- `pkg install python3.12 -y`

### 🗑️ REMOVE EXISTING LINKS

- `rm -f $PREFIX/bin/python $PREFIX/bin/python3 $PREFIX/bin/python-config $PREFIX/bin/python3-config $PREFIX/bin/pip $PREFIX/bin/pip3`

### 🔗 CREATE PYTHON LINKS

- `ln -sf python3.12 $PREFIX/bin/python3`
- `ln -sf python3 $PREFIX/bin/python`
- `ln -sf python3.12-config $PREFIX/bin/python3-config`
- `ln -sf python3.12-config $PREFIX/bin/python-config`

### 🔗 CREATE PIP LINKS

- `ln -sf pip3.12 $PREFIX/bin/pip3`
- `ln -sf pip3 $PREFIX/bin/pip`

### 🔍 CHECK VERSIONS

- `python --version`
- `pip --version`
