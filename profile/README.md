<p align="center">
  <img src="https://raw.githubusercontent.com/dgiot/dgiot/main/docs/logo.png" width="120" alt="DGIOT Logo" />
</p>

<h1 align="center">DGIOT — Industrial IoT Platform</h1>

<p align="center">
  <strong>300+ protocol adapters · Edge &amp; cloud · Energy, utilities &amp; manufacturing</strong>
</p>

<p align="center">
  <a href="https://github.com/dgiot/dgiot/stargazers"><img src="https://img.shields.io/github/stars/dgiot/dgiot?style=for-the-badge&color=f5c542" alt="Stars"></a>
  <a href="https://github.com/dgiot/dgiot/network/members"><img src="https://img.shields.io/github/forks/dgiot/dgiot?style=for-the-badge&color=0366d6" alt="Forks"></a>
  <a href="https://github.com/dgiot/dgiot/blob/main/LICENSE"><img src="https://img.shields.io/github/license/dgiot/dgiot?style=for-the-badge&color=2ea043" alt="License"></a>
</p>

---

## What is DGIOT?

**DGIOT** is an open-source Industrial IoT aggregation engine that connects sensors, PLCs, meters, drones, robots, and cameras — and turns raw data into actionable intelligence.

Unlike generic IoT platforms, DGIOT ships with **300+ protocol adapters** in the official catalog (Modbus, OPC UA, OPC DA, IEC 104, A11, DTU and more), runs on **edge devices or cloud**, and has been battle-tested in energy, utilities, and manufacturing.

### The Numbers

| Metric | Value |
|--------|-------|
| **GitHub Stars** | 4,836+ ★ (live badge above) |
| **Protocol Adapters** | 300+ (official catalog) |
| **Largest Single Deployment** | 928 gateways · 114,809 points · 16 oilfield plants |
| **Concurrency** | 30M simultaneous connections *(benchmark test)* |
| **Deploy Time** | 6 minutes *(official claim)* |
| **Docker Hub Pulls** | 6,300+ |

*Data verified 2026-09. Star count per GitHub, 2026-09 snapshot; concurrency is a benchmark result; deploy time is the vendor's official claim.*

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
│   Modbus │ OPC UA │ MQTT │ IEC 104 │ A11 │ DTU │ ...    │
└─────────────────────────────────────────────────────────┘
```

---

## Key Products Built on DGIOT

| Product | Status | Scale |
|---------|--------|-------|
| Oilfield Energy Data Pipeline | In production | 928 gateways · 114,809 points · 16 plants |
| Smart Circuit Breaker Platform | Prototype | Mobile + Admin dashboard |
| UAV Testing Platform | Under development | — |
| Maritime Safety Platform | Under development | — |

*Status reflects verified project stages as of 2026-09. New deployments will be added as they reach production.*

---

## Quick Start

```bash
# Clone the aggregation engine (Erlang/OTP 24.3 required)
git clone https://github.com/dgiot/dgiot.git
cd dgiot
make
```

> The platform is a compiled Erlang/OTP aggregation engine — see the [official README](https://github.com/dgiot/dgiot) for build prerequisites and deployment (Docker Compose / standalone). For an out-of-the-box edge + low-code experience, start with [iotStudio](https://github.com/dgiot/iotStudio) (Python, no compile step).

---

## Repositories

| Repo | Description | Stack |
|------|-------------|-------|
| [dgiot](https://github.com/dgiot/dgiot) | Core IoT aggregation engine | Erlang/OTP |
| [iotStudio](https://github.com/dgiot/iotStudio) | Edge platform & low-code application builder | Python + Vue 3 |
| [iotView](https://github.com/dgiot/iotView) | Dashboard & form framework | Vue 3 |
| [dgiot_dtu](https://github.com/dgiot/dgiot_dtu) | Windows edge gateway | C# |
| [iotApp](https://github.com/dgiot/iotApp) | Mobile low-code app | Java |
| [dgiot_doc](https://github.com/dgiot/dgiot_doc) | Documentation | Markdown |

---

## Selected Deployments

| Deployment | Detail |
|------------|--------|
| 🇨🇳 Daqing Oilfield (China) | Largest single deployment: 928 gateways · 114,809 points · 16 plants |

*Only deployments with verifiable contracts/records are listed. More references will be published as they are verified.*

---

## Community

🌐 [Website](https://www.dgiotcloud.cn) · [English Docs](https://github.com/dgiot/dgiot/tree/main/docs) · Discord — *Discord link pending verification (2026-09)*
💬 GitHub Discussions · https://github.com/dgiot

---

*License: Apache 2.0*
