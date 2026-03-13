# Solana Vault（金库示例，Devnet）

这是一个部署在 **Solana Devnet** 上的简单 **链上金库（Vault）程序**，允许用户安全地 **存款（Deposit）** 和 **取款（Withdraw）**。

该项目包含：

- 使用 **Anchor Framework** 编写的 Solana 智能合约
- 一个 **Next.js 前端 Demo** 用于与合约交互

---

## 🚀 在线演示

Vercel Demo：  
👉 **[https://solana-vault-demo.vercel.app/]**

> 该 Demo 前端允许用户连接钱包，并在 **Solana Devnet** 上与 Vault 程序进行交互。

---

## ✨ 功能

- 向 Vault 存入 SOL
- 从 Vault 提取 SOL
- 链上程序部署在 **Solana Devnet**
- 提供 Web 界面用于与合约交互
- 支持钱包连接进行交易

---

## 🛠 技术栈

### 区块链 / 智能合约

- Rust  
- Anchor Framework  
- Solana Program Library  

### 前端

- Next.js  
- Solana `web3.js`

### 部署

- Solana Devnet  
- Vercel（前端托管）

---


## ⚙️ 本地开发

### 1. 安装依赖

请确保已经安装：

- Rust
- Solana CLI
- Anchor Framework
- Node.js

### 2. 克隆仓库

```bash
git clone https://github.com/Jsirpro/Solana-vault-demo
cd Solana-vault-demo
```

### 3. 运行前端

```bash
cd app
npm install
npm run dev
```

---

## 🌐 网络

该程序部署在：

**Solana Devnet**

使用 Demo 时，请确保你的钱包已切换到 **Devnet 网络**。

---



## 📜 许可证

MIT License