# PharosBot
Please support Creator : https://t.me/winsnip 

Group Chat: https://t.me/winsnip_chat

My X : https://x.com/0xsoros

🔥 NEW TESTNET: PHAROS NETWORK 

💰 Reward: CONFIRMED

🚰 Faucet : https://testnet.pharosnetwork.xyz/

🤖 PHAROS BOT AVAILABLE
Features:

✅ AUTO SWAP (Wrap/Unwrap ETH)
✅ AUTO SEND ETH (Random Addresses)
✅ DAILY CHECK-IN (Automated)
🔜 AUTO ADD LIQUIDITY

## Installation
# 1. Clone the Repository
```
git clone https://github.com/winsnip/pharos-network-bot.git
cd pharos-network-bot
```
# 2. Install Dependencies
```
npm install
```
# 3. Set Private Key(without 0x)
```
nano .env
```
Input this
``` bash
PRIVATE_KEYS="yourprivatekey1"
MODE="manual"
#Remember Without 0X
```
## Auto Mode
# Create Screen 
```
screen -R pharos
```
# Start Bot
```
npm run start
```
# Update 
``` bash
git pull
#Run again with Start Bot
```

## Auto Mode Configuration Example
```
SWAP mode: auto
Total SWAP transactions per account: 15
Delay between SWAP transactions: 0.1 minutes
Gas price multiplier: 1.2
Account ETH amounts: 0.001 
Auto Send ETH: Enabled
ETH amount per auto-send: 0.00001
Random target addresses: 3
Schedule: 23 & 59
```
Your Screen will Showup like this
![alt text](https://github.com/Sorosjenaka/PharosBot/blob/main/Screenshot%20(178).png?raw=true)

## Cleanup & Reinstallation
```
sudo apt remove --purge nodejs npm libnode-dev -y
sudo apt autoremove -y
sudo rm -rf /usr/include/node /usr/lib/node_modules ~/.npm ~/.nvm
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
node -v && npm -v
```
