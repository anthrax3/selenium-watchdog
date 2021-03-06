![alt text](https://img.shields.io/badge/version-0.1-green.svg)
![alt text](https://img.shields.io/badge/python-2.7-blue.svg)
![alt text](https://img.shields.io/badge/OS-GNU%2FLinux-000000.svg)
[![alt text](https://img.shields.io/badge/donate-bitcoin-orange.svg)](https://blockchain.info/address/1Eggia3JXwWiR4mkVqztionNUfs2N3ghAd)

# selenium-watchdog

Automatically seek for changes on your files in your current directory recursively and refreshes the selenium browser to check the frontend changes.

## Requisites
 - Python2.7
 - GNU/Linux OS x64

## Installation
```
git clone https://github.com/m4n3dw0lf/selenium-watchdog
cd selenium-watchdog
pip install selenium watchdog
wget https://github.com/mozilla/geckodriver/releases/download/v0.13.0/geckodriver-v0.13.0-linux64.tar.gz
tar -xvzf geckodriver*
#or any other directory inside your $PATH variable
sudo cp geckodriver /usr/local/bin
chmod +x selenium-watchdog.py
#or any other directory inside your $PATH variable
sudo cp selenium-watchdog.py /usr/local/bin/selenium-watchdog
```

## Usage
 - Navigate to the project folder that you want to monitor file changes
 - Start to listen your web-server
 - Run:
```
selenium-watchdog <YOUR PROJECT URL>
```

## Example
```
selenium-watchdog http://localhost:1337
```
