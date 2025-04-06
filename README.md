# 🎲 Solana Dice Roll Smart Contract (Anchor Framework)

A simple, fun, and fully on-chain **Dice Rolling Game built on Solana** using the **Anchor framework**. This smart contract allows users to roll a dice and win rewards based on random outcomes — all deployed on the fast and low-cost Solana blockchain.

---

## 🚀 Features

- **Fair Dice Roll Logic** using pseudo-randomness
- **Solana Native Token Integration** (SOL / SPL)
- Built with the **Anchor Framework**
- Secure on-chain logic for provable outcomes
- Ready for frontend integration (React / Next.js)
- Includes unit tests and localnet setup

---

## Tech Stack

- **Solana Blockchain**
- **Rust / Anchor Framework**
- **Solana CLI & Anchor CLI**
- **Mocha for Testing**
- **TypeScript (for tests)**

---

## Installation

```bash
git clone https://github.com/love-luca/dice-roller-smart-contract.git
cd solana-dice-roll
anchor build
anchor test


## How It Works
Players call the roll_dice function.

The contract generates a random number between 1 and 6.

Rewards are distributed if the outcome matches certain conditions (e.g., roll a 6).

## Project Structure

├── programs/
│   └── dice_roll/
│       └── src/lib.rs         # Main Solana smart contract
├── tests/
│   └── dice-roll.ts           # Anchor tests
├── migrations/
├── Anchor.toml
├── Cargo.toml
└── README.md


## Contact

-Twitter [@defai_maxi](https://x.com/defai_maxi)
-Telegram [@rhettjel](https://t.me/rhettjel)