# 🐜 HormigasAIS — Sovereign Protocol Network

**LBH Protocol · P2P Swarm · Edge Computing · El Salvador 🇸🇻**

> *"Like ants, we build distributed intelligence — sovereign, antifragile, without a central server."*

---

## What is HormigasAIS?

A sovereign distributed protocol ecosystem built from Termux on Android in El Salvador.
No cloud dependency. No central server. Every node carries its own cryptographic identity.

**Founder:** [Cristhiam Leonardo Hernández Quiñonez (CLHQ)](https://www.linkedin.com/in/cristhiam-lbh-architect/)
**Protocol:** LBH v1.1 · DOI: [10.5281/zenodo.17767205](https://zenodo.org/records/17767205)

---

## ⚡ Key Metric
JSON → LBH binary : 89.3% bandwidth reduction
150 bytes         → 16 bytes per event
1B events/day     → 139 GB saved daily
---

## 🗺️ Ecosystem

| Repo | Description | Status |
|---|---|---|
| [LBH-Net](https://github.com/HormigasAIS/LBH-Net) | P2P swarm network · UDP autodiscovery · Ed25519 | v1.5.0 ✅ |
| [lbh-node-service](https://github.com/HormigasAIS/lbh-node-service) | Go microservice · REST + gRPC · SQLite | v0.2.0 ✅ |
| [HormigasAIS-AirCity](https://github.com/HormigasAIS/HormigasAIS-AirCity) | Airport UTM protocol · Drone authorization 🇸🇻 2027 | Active |
| [HormigasAIS-LBH-Protocol](https://github.com/HormigasAIS/HormigasAIS-LBH-Protocol) | RFC-LBH-0001 → 0006 · DOI certified | Published ✅ |
| [lbh-image-validator](https://github.com/HormigasAIS/lbh-image-validator) | IP validator · Ed25519 + SHA256 · Docker | v0.1.0 ✅ |
| [LBH-Signals](https://github.com/HormigasAIS/LBH-Signals) | Git signal bus between nodes | Active ✅ |
| [LBH-Nodes](https://github.com/HormigasAIS/LBH-Nodes) | Dynamic node registry | Active ✅ |

---

## 🏗️ Architecture
LBH Protocol (RFC-LBH-0006)
│
LBH Queue (SQLite)
│
Worker Pipeline
sign → verify → replicate
│
TCP Socket Server :9200
│
UDP Discovery :9199
│
Distributed Swarm Nodes
**Philosophy:**
hormigas    = nodos
feromonas   = señales LBH
colonia     = red distribuida
evaporación = TTL de señales
---

## 🔐 Protocol Credentials

- **RFC-LBH-0004** — Data Integrity (CRC-16 checksum)
- **RFC-LBH-0006** — Signal Standard (HMAC-SHA256)
- **DOI:** [10.5281/zenodo.17767205](https://zenodo.org/records/17767205)
- **Built:** Entirely from Android/Termux — zero cloud dependency

---

## 🌐 E-commerce Adapter

Real-time TikTok order processing using LBH binary protocol:
→ [Thrumanshow/lbh-tiktok-adapter](https://github.com/Thrumanshow/lbh-tiktok-adapter)

---

## 👤 Founder

| | |
|---|---|
| **Name** | Cristhiam Leonardo Hernández Quiñonez |
| **Role** | Solution Architect · LBH Protocol Author |
| **LinkedIn** | [cristhiam-lbh-architect](https://www.linkedin.com/in/cristhiam-lbh-architect/) |
| **Portfolio** | [thrumanshow.github.io/hormigasais-site](https://thrumanshow.github.io/hormigasais-site/) |
| **CV (EN)** | [cv_en.html](https://thrumanshow.github.io/lbh-tiktok-adapter/cv_en.html) |
| **CV (ES)** | [cv_es.html](https://thrumanshow.github.io/lbh-tiktok-adapter/cv_es.html) |
| **Location** | San Miguel, El Salvador 🇸🇻 |

---

*Built from Termux · Android · El Salvador 2026 · CLHQ / HormigasAIS*
