<p style="font-size:14px" align="right">
# Auto Bridge T3RN

## Linux & VPS
```
sudo apt update && sudo apt upgrade
```
```
sudo apt-get install screen
```
```
ufw allow ssh
```
```
ufw enable
```
```
sudo apt-get install python3 python3-pip
```
```
sudo apt-get install git
```
```
git clone https://github.com/Dalu26/t3rn-bot.git
```
```
cd t3rn-bot
```
```
python3 -m pip install -r requirements.txt
```
**Submit your EVM Private Keys**
```
nano privateKeys.py
```
**To save `CTRL+XY then Enter`**
### Run Bot
```
screen -S tbot
```
```
python3 run.py
```
**Exit Screen: CTRL+AD**

**If RPCs are not working, edit run.py and swap with your alchemy rpcs**

**Reopen Screen: screen -r tbot**

## Termux & WIndows
```
pkg upgrade && pkg update
```
```
termux-setup-storage
```
```
pkg install python
```
```
pkg install git
```
```
git clone https://github.com/Dalu26/t3rn-bot.git
```
```
cd t3rn-bot
```
```
pip install -r requirements.txt
```
**Submit your Private Keys Metamask**
```
nano privateKeys.py
```
**To save the env variables: `CTRL+XY then Enter`**
### Run bot
```
python run.py
```

**If RPCs are not working, edit run.py and swap with your alchemy rpcs**
