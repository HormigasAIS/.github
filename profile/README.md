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
| [lbh-spec](https://github.com/HormigasAIS/lbh-spec) | LBH protocol specification · DOI 10.5281/zenodo.17767205 | Published |
| [hormigasais-docs](https://github.com/Thrumanshow/hormigasais-docs) | Official LBH protocol documentation | Active |
| [lbh-node-service](https://github.com/HormigasAIS/lbh-node-service) | LBH microservice · REST + gRPC | Active |
| [xoxo-lbh-adapter](https://github.com/HormigasAIS/xoxo-lbh-adapter) | XOXO ↔ LBH-M2M adapter for robots and IoT | Active |
| [HormigasAIS-AirCity](https://github.com/HormigasAIS/HormigasAIS-AirCity) | Sovereign UTM authorization protocol 🇸🇻 | Active |
| [HormigasAIS.github.io](https://github.com/HormigasAIS/HormigasAIS.github.io) | Official landing page | Active |

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

## 📡 Official Channels

- 🎬 [TikTok](https://vt.tiktok.com/ZSguyUV56/) · [YouTube](https://www.youtube.com/watch?v=lL48tb4mg1M) · [Instagram](https://www.instagram.com/reel/De3Fjl2xF6H/) · [Facebook](https://www.facebook.com/share/p/19T3vHMgUR/)
- 🌐 [hormigasais.com](https://hormigasais.com) · [Medium](https://hormigasaiscristhiamquinonez.medium.com) · [X](https://x.com/hormigasaux)
- 🗂️ Full directory: [Feromona Hub](https://github.com/HormigasAIS-ux/HormigasAIS-Feromona-Hub) · Anchor: [Issue #3](https://github.com/HormigasAIS/.-github/issues/3)

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
