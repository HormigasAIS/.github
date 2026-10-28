# 🐜 HormigasAIS — Sovereign Protocol Network

**LBH Protocol · P2P Swarm · Edge Computing · El 🌎 • Nicaragua 🇳🇮 •  El Salvador 🇸🇻**

> *"Like ants, we build distributed intelligence — sovereign, antifragile, without a central server."*

---

## What is HormigasAIS?

A sovereign distributed protocol ecosystem built from Termux on Android in El Salvador.
No cloud dependency. No central server. Every node carries its own cryptographic identity.

**Founder:** [Cristhiam Leonardo Hernández Quiñonez (CLHQ)](https://www.linkedin.com/in/cristhiam-lbh-architect/)

**Protocol:** LBH v2.0 · DOI: [10.5281/zenodo.19177759](https://doi.org/10.5281/zenodo.19177759) (v1: [10.5281/zenodo.17767205](https://doi.org/10.5281/zenodo.17767205))

---

## ⚡ Key Metric

```text
JSON → LBH binary : 89.3% bandwidth reduction
150 bytes → 16 bytes per event
1B events/day → 134 GB saved daily (illustrative scenario)
```

---

## 🗺️ Ecosystem

| Repo | Description | Status |
|---|---|---|
| [lbh-spec](https://github.com/HormigasAIS/lbh-spec) | LBH protocol specification · DOI 10.5281/zenodo.19177759 | Published |
| [Lenguaje-Binario-HormigasAIS-](https://github.com/Thrumanshow/Lenguaje-Binario-HormigasAIS-) | LBH protocol repository · spec v2.0 | Published |
| [lbh-sdk](https://github.com/Thrumanshow/lbh-sdk) | Reference SDK (Python) · [PyPI](https://pypi.org/project/lbh-sdk/) | v0.3.1 |
| [hormigasais-docs](https://github.com/Thrumanshow/hormigasais-docs) | Official LBH protocol documentation | Active |
| [lbh-node-service](https://github.com/HormigasAIS/lbh-node-service) | LBH microservice · REST + gRPC | Active |
| [xoxo-lbh-adapter](https://github.com/HormigasAIS/xoxo-lbh-adapter) | XOXO ↔ LBH-M2M adapter for robots and IoT | Active |
| [HormigasAIS-AirCity](https://github.com/HormigasAIS/HormigasAIS-AirCity) | Sovereign UTM authorization protocol 🇸🇻 | Active |
| [HormigasAIS.github.io](https://github.com/HormigasAIS/HormigasAIS.github.io) | Official landing page | Active |

---

## 🏗️ Architecture

```text
LBH Protocol (RFC-LBH-0006)
│
LBH Queue (SQLite)
│
Worker Pipeline: sign → verify → replicate
│
TCP Socket Server :9200
│
UDP Discovery :9199
│
Distributed Swarm Nodes
```

**Philosophy:**

```text
hormigas    = nodos
feromonas   = señales LBH
colonia     = red distribuida
evaporación = TTL de señales
```

---

## 🔐 Protocol Credentials

- **RFC-LBH-0004** — Data Integrity (CRC-16 checksum)
- **RFC-LBH-0006** — Signal Standard (HMAC-SHA256)
- **DOI:** [10.5281/zenodo.19177759](https://doi.org/10.5281/zenodo.19177759) (v2.0) · [v1](https://doi.org/10.5281/zenodo.17767205)
- **Built:** Entirely from Android/Termux — zero cloud dependency

---

## 📡 Official Channels

- 🎬 [TikTok](https://vt.tiktok.com/ZSguyUV56/) · [YouTube](https://www.youtube.com/shorts/lL48tb4mg1M) · [Instagram](https://www.instagram.com/reel/De3Fjl2xF6H/) · [Facebook](https://www.facebook.com/share/p/19T3vHMgUR/)
- 🌐 [hormigasais.com](https://hormigasais.com) · [Medium](https://hormigasaiscristhiamquinonez.medium.com) · [X](https://x.com/hormigasaux)
- 🗂️ Full directory: [Feromona Hub](https://github.com/HormigasAIS-ux/HormigasAIS-Feromona-Hub) · Anchor: [Issue #3](https://github.com/HormigasAIS/.-github/issues/3)

---

## 👤 Founder

| | |
|---|---|
| **Name** | Cristhiam Leonardo Hernández Quiñonez |
| **Role** | Solution Architect · LBH Protocol Author |
| **LinkedIn** | [cristhiam-lbh-architect](https://www.linkedin.com/in/cristhiam-lbh-architect/) |
| **Website** | [hormigasais.com](https://hormigasais.com) |
| **Location** | San Miguel, El Salvador 🇸🇻 |

---

*Built from Termux · Android · El Salvador 2026 · CLHQ / HormigasAIS*
