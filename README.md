# 🔄 UPDATE Plume Swap Bot season 2
A lightweight Node.js bot that automatically swaps between PLUME and pUSD on the Plume chain. Ideal for automation and airdrop farming—especially for Plume Airdrop Season 2.

<img width="2558" height="1634" alt="image" src="https://github.com/user-attachments/assets/aa6a3685-aeb0-4442-9965-54841a1c3204" />

## 🚀 New Features
- Randomized daily swaps across 5 DEXs: Ambient, Rooster, Camelot, Curve and iZUMi.
  
- Auto-stakes to the Plume Portal daily with a random amount between 0.1 and 0.3 PLUME.
  
- Swap amounts and delays are randomized and fully configurable via the .env file.

- Designed to maximize points for Plume Airdrop Season 2.

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Kurisaitou/auto-swap-plume-season-2-in-6-DAPPs.git
```
```bash
cd auto-swap-plume-season-2-in-6-DAPPs
```
```bash
npm install
```

# ⚙️ Environment Setup
Create a .env file in the project root:
```bash
nano .env
```
Fill in your wallet details and configure your preferred settings:
```bash
RPC_URL=https://rpc.plume.org
CHAIN_ID=98866

# Accounts (at least 1)
PRIVATE_KEY_1=your_privatekey
WALLET_ADDRESS_1=your_address

# Optional extra accounts:
# PRIVATE_KEY_2=0xSECOND
# WALLET_ADDRESS_2=0xSECOND_ADDR

# Swap/stake params
MIN_PLUME=1
MAX_PLUME=2
MIN_TX=2
MAX_TX=5
MIN_DELAY=10
MAX_DELAY=30

MIN_TX_PER_DAY=2
MAX_TX_PER_DAY=5
MIN_DELAY_SEC=10
MAX_DELAY_SEC=60
```

## ▶️ Running the Bot
To start the bot:
```bash
node index.js
```
What the bot does:

- Randomly selects between Ambient, Rooster, Camelot, Curve and iZUMi DEXs for daily swaps.

- Executes a random number of swap transactions with randomized token amounts and delays.

- Automatically stakes a random amount (0.1 – 0.3 PLUME) daily to the Plume Portal to earn airdrop points.

## 🎯 Goal
Maximize your engagement with the Plume ecosystem and boost your chances of earning more rewards from Plume Airdrop Season 2 — automatically.

## 🔖 Tags
#plume #airdrop #swap #bot #crypto #web3 #automation #trading #pUSD #dex #stake #Ambient #Rooster #Camelot #Curve #iZUMi #portal-plume #plume-Season-2
