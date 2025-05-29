# Blockchain Traceability for Sustainable Agriculture

This project is aimed at enhancing traceability, authenticity, and sustainability in the agricultural supply chain using *Blockchain Technology*. It enables transparency from farm to fork by recording each stage of the agricultural process securely on a blockchain network.

## 🌱 Overview

In traditional agricultural supply chains, there's often a lack of transparency and trust. This system ensures that every stakeholder — *farmers, administrators, and consumers* — has access to reliable and tamper-proof information about agricultural products.

Built using:
- *Python*
- *Django*
- *SQLite*
- *HTML, CSS*
- *QR Code integration*

---

## 🚀 Key Features

### 👨‍🌾 Farmer Module
- Register and log in securely
- Add new products and farming details
- Generate unique QR codes for each product batch

### 👨‍💼 Admin Module
- Approve and manage registered farmers
- View submitted products and associated data
- Monitor system-wide transactions and activities

### 🧑‍💻 Consumer Module
- Scan QR code to verify product authenticity
- View complete traceability data including farmer info, cultivation, and transit records

---

## 🔐 Blockchain Integration

All product-related data is hashed and stored in a *blockchain ledger* to ensure immutability. Each transaction (like crop addition, approval, and sale) forms a block, which is chained to previous blocks to create an auditable history.

Benefits:
- Tamper-proof product traceability
- Fraud prevention
- Builds trust with end consumers

---

## 🧩 Tech Stack

| Layer        | Technologies |
|--------------|--------------|
| Backend      | Python, Django |
| Frontend     | HTML, CSS     |
| Database     | SQLite        |
| Blockchain   | Custom Python-based chain logic |
| Others       | QR Code Generation (Python Lib) |

---
