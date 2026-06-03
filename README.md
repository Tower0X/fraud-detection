# 🛡️ Sovereign Forensic NOC (Network Operations Center)

[![Expert Grade](https://img.shields.io/badge/Status-Mission--Critical-emerald?style=flat-square)](https://github.com/Tower0X/fraud-detection)
[![Tech Stack](https://img.shields.io/badge/Stack-FastAPI%20|%20React%20|%20ML-cyan?style=flat-square)](https://github.com/Tower0X/fraud-detection)

Welcome to the **Sovereign Forensic NOC**, an industrial-grade fraud detection platform engineered for real-time telemetry, high-fidelity visualization, and mission-critical decision support.

Designed for doctoral-level research and professional-grade security environments, this platform bridges the gap between complex ML inference and actionable forensic insights.

## 🚀 Architectural Pillars

### 1. High-Performance Telemetry Engine

- **Atomic State Distribution**: Driven by `Zustand` for zero-lag synchronization across the NOC.
- **60Hz Backpressure Control**: A sophisticated `useAlarm` hook utilizing `requestAnimationFrame` for rAF-batching, ensuring the UI remains responsive under extreme transaction loads (>1000 tx/s).
- **Industrial Signals**: Synth audio feedback and heartbeat monitoring for connection integrity.

### 2. Forensic Visualization (High-Fidelity)

- **Gate 0 (Biometric Auth)**: A kinetic entrance featuring a dynamic Node-Network Canvas and biometric-style identity verification.
- **Route 1 (Client Galaxy)**: 3D Parallax credit cards and circular Radar transaction simulators for behavioral visualization.
- **Route 2 (Supervisor Hub)**: The mission-control center with "Odometer" telemetry counters and a recursive forensic stream.

### 3. Bayesian Inference Terminal

- **Uncertainty Quantification**: Deep-dive analysis of fraud scores using Neural Confidence ($ \mu $) and Epistemic Uncertainty ($ \sigma $).
- **SHAP Factor Cascade**: Real-time attribution of fraud factors for explainable AI (XAI) and forensic auditability.

## 🛠️ Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React 18, TypeScript, Vite, Tailwind CSS, Framer Motion, Lucide |
| **Backend** | FastAPI, SQLAlchemy (SQLite/PostgreSQL), WebSockets, Pydantic |
| **ML Engine** | XGBoost, Balanced Random Forest, TreeSHAP, Bayesian Nexus |
| **State** | Zustand (Atomic Store), Context API |

## 📦 Quick Start Node

### Backend (Security Ingress)

```bash
cd app/backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate
pip install -r requirements.txt
python -m uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

### Frontend (NOC Terminal)

```bash
cd app/frontend
npm install
npm run dev
```

## 🛡️ Industrial Security Note

This project adheres to the **Industrial Sovereignty** directive:

- No telemetry data leaves the local node unless explicitly configured.
- Zero-dependency on proprietary black-box APIs for core inference.
- Full forensic auditability of every decision node.

---
**Developed for Tower0X | Sovereing Forensic Series**
