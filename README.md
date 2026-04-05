# 🎰 Foundry Smart Contract Lottery

A provably fair, decentralized raffle system built with Solidity and Foundry — powered by **Chainlink VRF v2.5** for verifiable randomness and **Chainlink Automation** for trustless execution.

## 🛠 Tech Stack

- **Solidity** `^0.8.19`
- **Foundry** — build, test, deploy
- **Chainlink VRF v2.5** — verifiable random winner selection
- **Chainlink Automation** — automatic raffle execution
- **Sepolia Testnet** — live deployment

## 📦 Installation

```bash
git clone https://github.com/youssef112w/foundry-smart-contract-lottery.git
cd foundry-smart-contract-lottery
forge install
```

## ⚙️ Setup

Create a `.env` file:

```env
SEPOLIA_RPC_URL=your_rpc_url
PRIVATE_KEY=your_private_key
ETHERSCAN_API_KEY=your_etherscan_key
```

## 🚀 Deploy

```bash
# Local
make deploy

# Sepolia
make deploy ARGS="--network sepolia"
```

## 🧪 Tests

```bash
forge test
forge coverage
```

## 📄 Contract

| Network | Address |
|---------|---------|
| Sepolia | [`0x23C319d67712D3cCF226E56E302bcBA64151E6a1`](https://sepolia.etherscan.io/address/0x23C319d67712D3cCF226E56E302bcBA64151E6a1) |


