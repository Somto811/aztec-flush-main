# aztec-flush

## Prerequisites

Node.js (v18 or higher)
Multiple Ethereum wallets with ETH for gas fees
Ethereum RPC endpoint (Alchemy, Infura, or your own node)
Basic understanding of running scripts and environment variables

# Step 1: Project Setup

## Requirements / Setup

Update system and install dependencies:
```bash
sudo apt install -y curl git build-essential
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
npm init -y
npm install ethers dotenv

```
# Create a new directory

```bash
mkdir aztec-flush-bot
cd aztec-flush-bot
```
# Initialize npm project

```bash
npm init -y
```

# Install dependencies

```bash
npm install ethers@6 dotenv
```

# Step 2: Create Environment File
Create a .env file in your project root and copy the contents of .env-example to .env


# Step 3: Running the Bot
 Run the bot
 you can create neew wallet with: node createwallet
 it saves the wallet keys to wallet.txt; fund wallet with eth

 # START FLUSH
 
 ```bash
node flush.js
```
