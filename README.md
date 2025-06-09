# BlockseBlock-task
# Blockchain Simulation Suite

This repository contains interactive, educational simulations demonstrating key blockchain concepts: consensus mechanisms, proof-of-work mining, and blockchain integrity.

---

## 📁 Contents

### ✅ `consensus_simulation.html`
A simulation that visually demonstrates how different consensus mechanisms select validators:
![image](https://github.com/user-attachments/assets/7728822e-5897-4128-bdbf-ac4496621246)



- **Proof of Work (PoW)**: Miners compete based on computational power.
- **Proof of Stake (PoS)**: Validators are chosen based on stake.
- **Delegated Proof of Stake (DPoS)**: Token holders vote for delegates to validate blocks.

**Features:**
- Dynamic generation of validators.
- Visual selection of winners for each mechanism.
- Comparison table for PoW, PoS, and DPoS.
- Console-style log for internal logic.

---

### ✅ `nonce_mining_simulation.html`
A live simulation of **Proof-of-Work** mining to demonstrate the mining process:
![image](https://github.com/user-attachments/assets/d37a9bb0-07f2-4f2e-a0ae-1be6bbaf4a29)


- Set **difficulty** (number of leading zeros in hash) and block data.
- Watch mining in real-time as the nonce is incremented until a valid hash is found.

**Outputs:**
- Total nonce attempts.
- Mining duration (seconds).
- Hash rate (hashes per second).
- Final block details: data, nonce, hash.

**Controls:**
- Start mining
- Stop mining
- Reset to start over

---

### ✅ `blockchain_simulation.js.html`
A blockchain integrity demonstration:
![image](https://github.com/user-attachments/assets/6db73362-1d78-4d83-91ba-94d5069c6fbd)

- Initializes a chain with 3 blocks.
- Allows tampering with data of block 1.
- Visualizes the impact of tampering on the entire chain (invalid blocks turn red).
- Option to recompute hashes to fix the chain.

**Features:**
- Live rendering of blockchain with block details.
- Visual status: valid (green) or invalid (red).
- Tampering simulation to illustrate immutability.

---

## 🚀 How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/blockchain-simulations.git
   cd blockchain-simulations

