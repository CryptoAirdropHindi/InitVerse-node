# How to run an InitVerse node

# Hardware Requirements:
VPS 2 Specifications:

CPU: 6 virtual cores RAM: 16 GB Storage: 400 GB SSD Bandwidth: 32 TB outbound + 
Unlimited inbound (200 Mbit/s connection) 
Price: Starting at around $12 per month Contabo VPS 2

# Update your system
```bash
sudo apt-get update
```
# Install Screen
```bash
apt install screen
```
- Downlad inichain file
```bash
wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64
```
- Give permission to the file
```bash
chmod +x iniminer-linux-x64
```
# Create a new screen session
```bash
screen -S Inichain
```
## Launch the InitVerse miner
```bash
./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672
```
![image](https://github.com/user-attachments/assets/1203a7c2-b5fa-4fb8-b352-f20619a190ad)
# Leave the screen
`CTRL+A+D`
# Check your miner activity
Go to https://genesis-testnet.yatespool.com/
![image](https://github.com/user-attachments/assets/61bbaf2f-2612-4e95-bf96-1cbe837ebf7b)
# Past your wallet address
![image](https://github.com/user-attachments/assets/0dc76d09-b45b-416f-9e6d-69566cf84242)
#The rewards are automatically sent to your address.
#You can check them on the explorer : https://genesis-testnet.iniscan.com/
![image](https://github.com/user-attachments/assets/e237861c-2ee5-4b5c-841b-e290475285a5)

# Check logs
```bash
screen -r Inichain
```
- Don’t forget to leave it with CTRL+A+D

  # Thank’s for reading
  If you need help you can join https://t.me/Crypto_airdropHM

Disclaimer : Not a financial Advice an education tutorial do your own research
