---
sidebar_position: 2
---

# BAIclaw Agent Wallet

Agent Wallet is a locally secured Web3 wallet designed specifically for AI agents. It provides AI agents with the ability to interact with blockchains, enabling AI to autonomously perform various Web3 operations.

## What is Agent Wallet?

Agent Wallet is a special type of wallet designed for AI scenarios:

- **Local Secure Storage**: Wallet keys are encrypted and stored locally, never uploaded to the cloud
- **AI Autonomous Operations**: Once configured, AI can directly execute on-chain transactions
- **Feature-Rich**: Supports transfers, swaps, liquidity management, and many other Web3 skills
- **x402 Protocol Support**: Access paid resources based on the x402 protocol

:::info[How Agent Wallet Differs from Regular Wallets]
Regular wallets are manually operated by humans, while Agent Wallet is authorized for use by AI agents, enabling AI to execute on-chain operations on your behalf.
:::

## Core Features

Once Agent Wallet is configured, your AI agent will have the following capabilities:

| Feature | Description |
|---------|-------------|
| **Self Top-Up** | AI can autonomously top up as needed to ensure sufficient funds for operations |
| **Transfer** | Send cryptocurrency to other addresses |
| **Token Swap** | Exchange between different tokens |
| **Liquidity Management** | Participate in DeFi liquidity pool management |
| **x402 Payment** | Access AI resources and services that require payment |

## Creation Process

### Prerequisites

:::warning[Important Prerequisite]
You **must add and configure a BAI API Key before** creating an Agent Wallet, otherwise the wallet cannot be created. Learn [how to obtain an API Key](operation-guide/Get-API-Key.md)
:::

### Steps

1. **Import Private Key**
   - Import the wallet private key associated with your BAI API Key
   - Currently only **TRON addresses** are supported
   - The address corresponding to the private key must match the account address of the API Key

2. **Set Master Password**
   - Must be at least 8 characters
   - Must include uppercase and lowercase letters, numbers, and special characters
   - Used to encrypt and protect the local wallet file

:::danger[Password Security Warning]
The platform **does not back up your master password**. If lost, it **cannot be recovered**. Please keep it safe — using a password manager is strongly recommended.
:::

## Management & Maintenance

### Modifying API Key

- If the current API Key already has an Agent Wallet bound to it, you must **delete the existing Agent Wallet** before modifying the API Key

:::warning[Deletion Warning]
Deletion will result in the wallet, keys, and configuration being **permanently deleted and unrecoverable**. Please ensure you have backed up any necessary information.
:::

## Usage Examples

After successfully creating an Agent Wallet, you can ask BAIclaw to help you with various Web3 operations:

| Scenario | Example Command |
|----------|-----------------|
| Check Exchange Rate | "Check the USDT to TRX exchange rate" |
| Balance Inquiry | "Show my BAI account balance" |
| Order History | "Show my recent order history" |
| Token Transfer | "Transfer 100 USDT to the specified address" |

## FAQ

**Q: What is the fundamental difference between Agent Wallet and a regular wallet?**  
A: Agent Wallet is a wallet authorized for AI use. AI can autonomously execute operations within the scope you define; a regular wallet is entirely under your manual control.

**Q: Why do I need to import a private key?**  
A: The private key is the sole credential for blockchain assets. Only after importing the private key can AI sign and send transactions on your behalf.

**Q: What if I forget my master password?**  
A: Unfortunately, the platform does not store the master password, and the wallet cannot be recovered if forgotten. Please keep it safe — we recommend writing it down on paper or using a password manager.

**Q: Can I modify a wallet that has already been created?**  
A: You cannot modify it directly. You need to delete the existing wallet first, then create a new one.

**Q: Which blockchains are supported?**  
A: Currently only the TRON network is supported. More chains may be supported in the future.


---

:::tip[Need Help?]
If you encounter issues while configuring Agent Wallet, please check:
1. Whether the API Key is correctly configured
2. Whether the address corresponding to the private key matches the API Key account
3. Whether the master password meets the complexity requirements
:::
