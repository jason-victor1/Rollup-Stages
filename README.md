# Rollup Stages and ZKSync Maturity 

This repository provides insights into **Layer 2 (L2) Rollup stages**, the decentralization framework, and the current maturity of **ZKSync Era**.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Rollup Stages](#rollup-stages)
3. [ZKSync Era Overview](#zksync-era-overview)
4. [Risk Analysis Table](#risk-analysis-table)
5. [Conclusion](#conclusion)

---

#### **Introduction**
- Layer 2 (L2) chains are evaluated based on their **maturity** and are categorized into **stages**.
- The **L2B team** provides an opinionated assessment to encourage progression toward **greater decentralization**.

---

### **Rollup Stages**
The maturity of a rollup progresses through three **stages**:

1. **Stage 0**
   - Governance is controlled by **operators** and a **security council**.
   - Critical decisions are managed by a **trusted group**.
   - The open-source software allows the reconstruction of the L2 state from **L1 data** which ensures transparency.
   - Users can exit the rollup but may need **manual intervention** from an entity or operator.
   - Exit Window: Users can leave within **seven days**. However, it does requires specific actions.

2. **Stage 1**
   - Governance transitions to **smart contracts**.
   - The **security council** still plays a role which mainly for solving issues like **bugs**.
   - The proof system becomes **decentralized** which enables submission of validity proofs.
   - The **exit mechanism** is improved:
     - Users can exit **independently** without requiring operator involvement.

3. **Stage 2**
   - Rollup achieves **full decentralization**.
   - Governance is managed entirely by **smart contracts**.
   - The proof system becomes **permissionless**.
   - The exit mechanism is fully decentralized.
   - The role of the security council becomes **minimal** which focuses only on addressing errors.

---

### **ZKSync Era Overview**
- ZKSync Era is currently at **Stage 0**.
- A detailed **risk analysis** identifies key factors affecting its maturity:
   - **Data Availability**:
     - Ensures L2 state reconstruction from L1 data for transparency.
   - **State Validation**:
     - Verifies transactions using **zero-knowledge proofs**.
   - **Sequencer Failure**:
     - Allows transactions to still be submitted to L1. However, they may not be enforced immediately.
   - **Proposer Failure**:
     - Halts withdrawals and transaction execution if the proposer fails.
   - **Exit Window**:
     - Currently, there is **no window** for exits during upgrades.

---

### **Risk Analysis Table**
ZKSync and other rollups are assessed for maturity and categorized into stages:

| **Name**          | **Type**             | **Stage** | **Purpose**        | **Total Value Locked (TVL)** |
|--------------------|----------------------|-----------|--------------------|-----------------------------|
| Arbitrum One      | Optimistic Rollup    | Stage 1   | Universal          | $15.76B                     |
| Base              | Optimistic Rollup    | Stage 0   | Universal          | $6.73B                      |
| OP Mainnet        | Optimistic Rollup    | Stage 1   | Universal          | $5.82B                      |
| Blast             | Optimistic Rollup    | Stage 0   | Universal, DeFi    | $2.58B                      |
| Linea             | ZK Rollup            | Stage 0   | Universal          | $1.14B                      |
| ZKSync Era        | ZK Rollup            | Stage 0   | Universal          | $1.12B                      |
| Scroll            | ZK Rollup            | Stage 0   | Universal          | $912.66M                    |
| Starknet          | ZK Rollup            | Stage 0   | Universal          | $688.89M                    |

---

### **Conclusion**
- Rollup stages provide a clear **framework** for evaluating the decentralization and maturity of Layer 2 chains.
- Understanding the requirements for each stage helps assess the **progress** and **risks** of rollups.
- ZKSync Era and other rollups aim to evolve through these stages to achieve **full decentralization**.

