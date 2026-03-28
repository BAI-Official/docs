---
sidebar_position: 2
---
# Get Web3 Wallet Private Key

A private key is the sole credential for controlling your assets on the blockchain. When configuring BAIclaw Agent Wallet, you need to import the wallet private key associated with your BAI API Key. This guide will walk you through safely exporting your private key from common Web3 wallets.

:::danger[Security Warning]
**Private key = full control of your assets.** Anyone who holds your private key can directly transfer all your funds. Treat your private key like a bank password — **never** reveal it to anyone.
:::

## Before You Begin

Before exporting your private key, make sure the following security conditions are met:

- ✅ You are in a **secure, private environment** where no one else can see your screen
- ✅ Your computer is **not being remotely controlled** (close remote access software such as TeamViewer, AnyDesk, etc.)
- ✅ Your device is **free of malware** (it is recommended to run a security scan beforehand)
- ✅ You will not send the private key via screenshots, messaging apps, or email

:::tip[Recommendation]
After exporting the private key, paste it directly into BAIclaw's Agent Wallet configuration. **Do not** save the private key in your clipboard, notepad, or any file. Clear your clipboard after completing the configuration.
:::

---

## Wallet Export Guides

### TronLink

1. Open the **TronLink** browser extension
2. Click **Wallet Details** in the top-left corner of the page
3. Select **Export Wallet / Private Key** from the menu
4. Enter your wallet password to verify
5. Copy the displayed private key

### MetaMask

1. Open the **MetaMask** browser extension
2. Click the **Account** icon in the top-left corner
3. Click the **three dots (⋮)** on the right side of the target account, then select **"Account Details"**
4. Click **"Show Private Key"**
5. Enter your wallet password to verify
6. Copy the displayed private key

### OKX Wallet

1. Open the **OKX Wallet** browser extension
2. Click the **Wallet Management icon** in the top-left corner (or go to **Settings → Wallet Management**)
3. Click the **three dots (⋮)** or the **"Manage"** icon on the right side of the current wallet
4. Select **"Back Up Wallet"** or **"View Private Key"**
5. Enter your wallet password to verify
6. Copy the displayed private key

### Binance Wallet

1. Open the **Binance Wallet** browser extension
2. Click the **Settings (gear)** icon in the top-right corner
3. Select **"Account Management"**
4. Click **"Export Private Key"**
5. Enter your wallet password to verify
6. Copy the displayed private key

### TokenPocket

1. Open the **TokenPocket** browser extension
2. Click the **wallet icon** in the top-left corner to enter the details page
3. Click **"Details"** or **"Wallet Management"**
4. Find the **"Export Private Key"** option
5. Enter your wallet password to verify
6. Copy the displayed private key

:::info[About Password Verification]
Almost all wallets require you to enter a password when exporting a private key. This is a built-in security mechanism. If you have forgotten your wallet password, you will need to recover your wallet using your seed phrase first, then reset your password before exporting.
:::

---

## Security Tips After Exporting

After exporting your private key and configuring Agent Wallet, please take the following steps:

1. **Clear your clipboard** — Copy a piece of unrelated text to overwrite the private key in your clipboard
2. **Check your browser** — Make sure no extensions or web pages have recorded your private key
3. **Do not save screenshots** — Screenshots may be automatically uploaded by cloud sync services

---

## FAQ

**Q: Why does BAIclaw need my private key?**
A: BAIclaw's Agent Wallet requires the private key to sign and execute on-chain transactions on your behalf. The private key is encrypted and stored locally only — it is never uploaded to any server.

**Q: What if my wallet is not listed above?**
A: Most Web3 wallets offer a private key export feature, typically found under **Settings → Security → Export Private Key**. If you can't find it, please refer to your wallet's official documentation.

**Q: What format is the exported private key in?**
A: A private key is typically a 64-character hexadecimal string (e.g., `a1b2c3d4...`).

**Q: What is the difference between a private key and a seed phrase?**
A: A seed phrase (usually 12 or 24 English words) can derive multiple private keys. In BAIclaw, you only need to import a single private key.

**Q: Can I still use my original wallet after exporting the private key?**
A: Yes. Exporting the private key is a read-only operation and does not affect your original wallet in any way. Your original wallet and Agent Wallet will share the same address and assets.

---

:::tip[Next Step]
After successfully obtaining your private key, go to [Create Agent Wallet](../Agent-Wallet.md) to complete the wallet configuration.
:::
