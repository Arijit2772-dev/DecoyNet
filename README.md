# 🛡️ DecoyNet

### Agentic AI for Securing Home IoT Devices Using Deception & Autonomous Defence

[![E-Raksha 2026](https://img.shields.io/badge/E--Raksha-Hackathon%202026-00d4ff?style=for-the-badge)](https://edc.iitd.ac.in)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge)]()
[![Team](https://img.shields.io/badge/Team-Big__dawgs-ff6b35?style=for-the-badge)]()

> **Turn your home network into a smart, self-defending system.**

---

## 🎯 Problem Statement

**E-Raksha Hackathon 2026 | Problem Statement I | eDC IIT Delhi × CyberPeace**

Design an agentic AI-powered IoT security system that protects home users from cyberattacks using autonomous threat detection, deception technologies (honeypots/honeytokens), real-time response, and edge-based firewall capabilities.

### Why This Matters

- **15B+** IoT devices globally by 2025
- **57%** of IoT devices vulnerable to attacks
- **98%** of home networks lack proper security
- **₹50,000+** cost of enterprise solutions

---

## 💡 Our Solution

**DecoyNet** is a plug-and-play AI security appliance that protects home networks through:

| Feature | Description |
|---------|-------------|
| 🔍 **Auto Discovery** | Detect all IoT devices, profile behavior, assess risk |
| 🪤 **Deception Layer** | Deploy honeypots & honeytokens to trap attackers |
| 🛡️ **Autonomous Response** | AI-powered auto-block, quarantine, segmentation |
| 📊 **Real-Time Dashboard** | Consumer-friendly monitoring & alerts |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────┐
│                    DASHBOARD                         │
│            Web • Mobile • SMS Alerts                 │
├─────────────────────────────────────────────────────┤
│                 RESPONSE ENGINE                      │
│          Block • Quarantine • Segment                │
├─────────────────────────────────────────────────────┤
│              DECEPTION ORCHESTRATOR                  │
│         Honeypots • Honeytokens • Traps              │
├─────────────────────────────────────────────────────┤
│              INTELLIGENCE ENGINE                     │
│        ML Anomaly Detection • Classification         │
├─────────────────────────────────────────────────────┤
│                   EDGE AGENT                         │
│      Packet Capture • Device Fingerprinting          │
└─────────────────────────────────────────────────────┘
                        │
                        ▼
               [ Raspberry Pi ]
```

---

## ✨ Key Features

### 1. IoT Device Discovery & Risk Profiling
- Auto-detect all devices (TVs, cameras, bulbs, wearables)
- Baseline behavior modeling
- Identify vulnerabilities (outdated firmware, open ports)
- Real-time risk scoring

### 2. Dynamic Deception Layer
- **Honeypots:** Fake cameras, NAS, smart devices
- **Honeytokens:** Fake credentials that trigger alerts
- Trap attackers while protecting real assets

### 3. Autonomous Threat Response
- ML-based anomaly detection (Isolation Forest)
- Auto-block malicious IPs
- Quarantine compromised devices
- Network micro-segmentation

### 4. Edge-Based Processing
- Runs on Raspberry Pi
- Low-latency local inference
- **Privacy-first:** Data never leaves your home

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Languages** | Python, Go |
| **ML/AI** | PyTorch, Scikit-learn, ONNX |
| **Networking** | Scapy, Nmap, Zeek |
| **Edge** | Raspberry Pi, Docker |
| **Dashboard** | Streamlit |
| **Deception** | Custom Framework, Cowrie |

---



## 👥 Team Big_dawgs

| Member | Role | GitHub |
|--------|------|--------|
| **Arijit** | ML & Systems | [@Arijit2772-dev](https://github.com/Arijit2772-dev) |
| **Prabinder** | Cybersecurity & Backend | [@prabindersinghh](https://github.com/prabindersinghh) |
| **Anish** | Frontend & Integration | - |

**Institute:** Thapar Institute of Engineering & Technology (TIET), Patiala

---

## 🏆 Team's Prior Work

| Project | Description | Links |
|---------|-------------|-------|
| **CyberSentinel** | AI-powered Intrusion Detection System with real-time MITM/ARP detection & auto-response | [Demo](https://cybersentinelpro2.vercel.app/) • [Code](https://github.com/prabindersinghh/CyberSentinel) |
| **ReLink** | Smart file transfer system for unstable networks | [Code](https://github.com/Arijit2772-dev/trackshift) |
| **CampusGrid** | P2P compute sharing platform | [Code](https://github.com/Arijit2772-dev/p2p-grid) |

---

## 📅 Development Roadmap

- [x] Problem analysis & solution design
- [x] Architecture planning
- [ ] Device discovery module
- [ ] ML anomaly detection
- [ ] Honeypot framework
- [ ] Response engine
- [ ] Dashboard UI
- [ ] Edge deployment
- [ ] Testing & demo

---

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <strong>E-Raksha Hackathon 2026</strong><br>
  eDC IIT Delhi × CyberPeace<br>
  BECon'26 & AI Impact Summit'26
</p>

<p align="center">
  <i>"We don't just detect threats. We trap, learn, and fight back."</i>
</p>
