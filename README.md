# 🎯 HUNTER V2 | Ultra Clean Pro Terminal

A high-performance Digit Differs trading engine with a minimalist terminal interface. Built for speed, safety, and multi-account management.

## 🚀 Setup Instructions

1. **Generate API Token**:
   - Go to [Deriv API Settings](https://app.deriv.com/account/api-token).
   - Select **"Read"** and **"Trade"** checkboxes.
   - Name it "HunterBot" and click **Create**.
   - Copy the token string.

2. **Launch Terminal**:
   - Open your GitHub Pages URL.
   - Click **+ ADD** in the top right.
   - Enter a Profile Name (e.g., "Main Account") and paste your token.

3. **Configure Strategy**:
   - **Market**: Select your preferred Volatility Index.
   - **Stake**: Starting amount (Default $1.50).
   - **Predict**: The digit you think the last tick will NOT be.

## 🛠 Pro Features

- **Multi-Profile**: Save multiple accounts and switch instantly.
- **Manual Recovery**: Use the `RESET STAKE` button to drop the Martingale chain back to base without stopping the bot.
- **Visual History**: Live table tracking your last 20 trades.
- **Audio Feedback**: Distinct win/loss sound alerts.

## ⚠️ Risk Protocol

This bot uses an **11x Martingale** multiplier.
- **Step 1:** $1.50
- **Step 2:** $16.50
- **Step 3:** $181.50
- **Step 4:** $1,996.50

**ALWAYS** set a Stop Loss. If the stake reaches a level that makes you uncomfortable, hit **RESET STAKE** immediately to protect your capital.

---
*Disclaimer: For educational use only. Trading involves risk.*
