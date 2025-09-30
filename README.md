# Deflow-ai
AI Agent perp Terminal 
Here’s the **final `README.md` file** you can copy directly into your repo 👇

---

````markdown
# 🚀 PerpNova Agent  

**PerpNova Agent** is an AI-powered blockchain trading assistant.  
It combines **Solscan**, **Dexscreener**, and **Orderly (Perps)** into one tool.  

- 📊 View wallet balances & tokens (Solscan)  
- 🔎 Discover hot tokens (Dexscreener)  
- 📈 Check perp markets & simulate trades (Orderly)  
- 🎨 Fancy CLI output — easy to demo live  

---

## ⚡ Judge Quickstart  

```bash
npm install
npm run demo
````

➡️ Instantly see mock portfolio, token scans, and perp markets in the terminal.
➡️ No API keys required for demo.

---

## 🛠 Full Setup

1. **Clone & install**

```bash
git clone <your-repo-url>
cd solscan-hedera-orderly-agent
npm install
```

2. **Run demo (safe mock mode)**

```bash
npm run demo
```

3. **Optional: Add API keys for live data**
   Copy `.env.example` → `.env` and fill in:

```ini
SOLSCAN_API_KEY=your-solscan-key
ORDERLY_API_KEY=your-orderly-key
ORDERLY_API_SECRET=your-secret
ORDERLY_WS_URL=wss://stream.orderly.network
```

---

## 🎥 Demo Output

When you run `npm run demo`, you’ll see something like:

```
🚀 PerpNova Agent Demo
=======================

📊 Wallet Portfolio
┌──────────┬───────────┬─────────┐
│ Token    │ Balance   │ USD     │
├──────────┼───────────┼─────────┤
│ SOL      │ 120.5     │ $21,840 │
│ USDC     │ 9,500     │ $9,500  │
└──────────┴───────────┴─────────┘

🔎 Dexscreener Hot Tokens
┌─────────┬─────────┬──────────┐
│ Token   │ Mkt Cap │ 24h Vol  │
├─────────┼─────────┼──────────┤
│ PEPE    │ $30M    │ $1.5M    │
│ FLOKI   │ $18M    │ $950K    │
└─────────┴─────────┴──────────┘

📈 Orderly Perp Snapshot
┌──────────┬─────────┬──────────┐
│ Symbol   │ Price   │ 24h Vol  │
├──────────┼─────────┼──────────┤
│ ETH-USDT │ $3,240  │ $120M    │
│ SOL-USDT │ $172.5  │ $85M     │
└──────────┴─────────┴──────────┘
```

---

## ✅ Judge Checklist

* [ ] Run `npm install`
* [ ] Run `npm run demo`
* [ ] See wallet, token, and perp tables in terminal
* [ ] (Optional) Add keys → see live blockchain data
* [ ] Confirm safe mock demo works without keys

