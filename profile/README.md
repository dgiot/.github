<p align="center">
  <img src="https://raw.githubusercontent.com/dgiot/dgiot/main/docs/logo.png" width="120" alt="DGIOT Logo" />
</p>

<h1 align="center">DGIOT — Industrial IoT Platform</h1>

<p align="center">
  <strong>6-minute deployment · 10M+ device connections · Telecom-grade reliability</strong>
</p>

<p align="center">
  <a href="https://github.com/dgiot/dgiot/stargazers"><img src="https://img.shields.io/github/stars/dgiot/dgiot?style=for-the-badge&color=f5c542" alt="Stars"></a>
  <a href="https://github.com/dgiot/dgiot/network/members"><img src="https://img.shields.io/github/forks/dgiot/dgiot?style=for-the-badge&color=0366d6" alt="Forks"></a>
  <a href="https://github.com/dgiot/dgiot/blob/main/LICENSE"><img src="https://img.shields.io/github/license/dgiot/dgiot?style=for-the-badge&color=2ea043" alt="License"></a>
  <a href="https://discord.gg/xxx"><img src="https://img.shields.io/badge/Discord-Join%20us-5865F2?style=for-the-badge&logo=discord" alt="Discord"></a>
</p>

---

## What is DGIOT?

**DGIOT** is an open-source Industrial IoT platform that connects anything to anything — sensors, PLCs, meters, drones, robots, cameras — and turns raw data into actionable intelligence.

Unlike generic IoT platforms, DGIOT ships with **300+ industrial protocol adapters** out of the box, runs on **edge devices or cloud**, and has been battle-tested in energy, utilities, and manufacturing.

### The Numbers

| Metric | Value |
|--------|-------|
| **GitHub Stars** | 12,237 ★ |
| **Developer Community** | 70,000+ |
| **Enterprise Deployments** | 200+ |
| **Protocol Adapters** | 300+ |
| **Largest Single Deployment** | 928 gateways, 114,809 points |
| **Concurrency Verified** | 30M simultaneous connections |
| **Uptime** | 99.9999% |
| **Deploy Time** | 6 minutes |

---

## Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    Application Layer                     │
│   Digital Twin │ Dashboard │ SCADA │ Mobile │ Reports   │
├─────────────────────────────────────────────────────────┤
│                    Intelligence Layer                    │
│   Stream Compute │ Rules Engine │ AI Models │ Alerts    │
├─────────────────────────────────────────────────────────┤
│                      Core Layer                          │
│   Device Model │ Data Pipeline │ MQTT Broker │ Storage  │
├─────────────────────────────────────────────────────────┤
│                    Protocol Layer                        │
│   Modbus │ OPC UA │ MQTT │ IEC 104 │ A11 │ 300+ more   │
└─────────────────────────────────────────────────────────┘
```

---

## Key Products Built on DGIOT

| Product | Status | Scale |
|---------|:------:|-------|
| **UAV Automated Testing** | Production | 60 units/day, military certified |
| **Energy Data Pipeline** | Production | 928 gateways, 652M data points |
| **Smart Circuit Breaker** | Prototype | Mobile + Admin dashboard |
| **Maritime Safety Platform** | Production | 200+ coast guard vessels |
| **Smart Grid Metering** | Production | 7 cities, 120K smart meters |

---

## Quick Start

```bash
# Clone and run — that's it
git clone https://github.com/dgiot/dgiot.git
cd dgiot
docker-compose up -d

# Open http://localhost:5080
# Default: admin / dgiot_admin
```

[Full Documentation →](https://docs.dgiotcloud.cn)

---

## Repositories

| Repo | Description | Stack |
|------|-------------|-------|
| [dgiot](https://github.com/dgiot/dgiot) | Core IoT platform | Erlang/OTP |
| [iotStudio](https://github.com/dgiot/iotStudio) | Low-code application builder | Vue 3 |
| [iotView](https://github.com/dgiot/iotView) | Dashboard & form framework | Vue 3 |
| [dgiot_dtu](https://github.com/dgiot/dgiot_dtu) | Windows edge gateway | C# |
| [iotApp](https://github.com/dgiot/iotApp) | Mobile low-code app | Java |
| [dgiot_doc](https://github.com/dgiot/dgiot_doc) | Documentation | Markdown |

---

## Who Uses DGIOT?

- 🇸🇦 **Saudi SEC** — First Chinese IoT platform in Middle East power grid
- 🇯🇵 **Toppan (Japan)** — 15M ZETA tag stress test, 1B data points

---

## Community

- 🌐 [Website](https://www.dgiotcloud.cn) · [English Docs](https://docs.dgiotcloud.cn/en)
- 💬 [Discord](https://discord.gg/xxx) · [GitHub Discussions](https://github.com/dgiot/dgiot/discussions)

---

<p align="center">
  <sub>Based in Dallas, TX, USA · Apache 2.0 License · Built with ❤️ by the DGIOT community</sub>
</p>
