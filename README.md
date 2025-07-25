# 🎓 RegisTu! - Diploma Validation via Distributed Blockchain

**RegisTu!** is a Java-based application that *simulates* a secure, decentralized system for diploma registration and validation by academic institutions. The system applies foundational blockchain principles inspired by Bitcoin, including:

- A **distributed ledger** shared across multiple nodes to ensure data transparency and resilience  
- **Proof-of-Work (mining)** to validate new blocks and prevent tampering  
- **Public and private key cryptography** for digital identity and secure transaction signing  
- **Digital signatures** to authenticate diploma records and verify their source
- **Merkle trees** to efficiently structure and verify diploma transactions within each block
- **Immutable blocks**, where each block contains a hash of the previous one, ensuring the integrity of the entire chain  
- **Role-based access control**, distinguishing between Students (viewers) and Registrars (submitters)  

This system offers a practical implementation of blockchain for academic certification, emphasizing decentralization, security, and trustless verification.

---

## 👤 Login UI (Client View)

- Users log in securely with cryptographic verification  
- The interface dynamically adapts to the user's role:
  - **Student:** View and verify diplomas
  - **Registrar:** Register and issue diplomas to the blockchain

---

## 🖥️ Node UI (Server View)

- Each node runs a **NodeFrame**, acting as a peer in the blockchain network  
- Nodes validate transactions, mine blocks, and maintain consensus  
- Nodes synchronize blockchain data to ensure consistency across the network

---

## How to clone:

### Requirements

- Java 8 or later  
- [FlatLaf 3.5.2](https://www.formdev.com/flatlaf/) (UI look & feel library) **Must be added after cloning**

---

### Cloning the Project

```bash
git clone https://github.com/Benquerer/Diploma-Blockchain.git
cd Diploma-Blockchain
