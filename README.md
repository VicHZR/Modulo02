# 📊 Non-Functional Testing & Performance Engineering Framework

<p align="left">
  <a href="https://jmeter.apache.org">
    <img src="https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white" />
  </a>
  <a href="https://smartbear.com">
    <img src="https://img.shields.io/badge/SoapUI-6CB33E?style=for-the-badge&logo=smartbear&logoColor=white" />
  </a>
  <a href="https://usebruno.com">
    <img src="https://img.shields.io/badge/Bruno-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  </a>
  <a href="https://github.com">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🚀 Overview

A specialized **Non-Functional Testing (NFT) Framework** engineered to audit backend performance, load resilience, and service contract integration. 

Utilizing the **GitHub REST API** and enterprise endpoints as testing targets, this repository compiles structured automation suites via **JMeter, SoapUI, and Bruno**. It focuses on benchmarking transaction latencies, stress limits, and service layer reliability under concurrent thread distribution.

🎯 Focus: **Performance benchmarking, load testing, SOAP/REST service validation, and load-resilience infrastructure engineering.**

---

## 🎯 Key Technical Features

- ⏱️ **Performance & Load Simulation:** Concurrency load profiles configured via **Apache JMeter** to pinpoint database degradation and application bottlenecks.
- 🔌 **Enterprise SOAP & REST Validation:** Comprehensive integration testing suites designed within **SoapUI** and **Bruno** to validate XML/JSON schemas and endpoints.
- 📋 **Structured Test Planning (NFT):** A formal architectural Test Plan documenting boundary parameters, high-availability thresholds, and service-level objectives (SLOs).
- 🔑 **Dynamic Session Management:** Automated runtime handling of environment attributes and API variables to ensure decoupled and clean suite execution.

---

## 🏗️ Project Architecture Layout

The testing artifacts are organized into isolated modules tailored for automated runner engines:

```text
Modulo02/
│
├── GitHub Api/       # Automated REST verification collections and configurations (Bruno/JMeter)
├── SOAP UI/          # XML Schema validation suites and SOAP endpoint testing packages
├── Test Plan/        # Non-functional requirements (NFRs), boundaries, and strategy manifest
└── README.md         # Core technical engineering documentation
```

---

## 📊 Impact (CV-Level Highlights)

- 📈 **Identified Latency Regressions:** Designed load execution threads to simulate multi-user traffic, mapping structural server response degradation.
- 🛡️ **Enforced Contract Integrity:** Automated XML/JSON integration test checkpoints, ensuring stable interface contracts between internal backend layers.
- ⚙️ **Mitigated Concurrency Issues:** Formulated precise assertions to isolate system errors, transaction timeouts, and server execution failures under load.
- 📉 **Optimized Testing Overhead:** Replaced manual endpoint verifications with reusable collection templates, slashing technical test deployment lifecycles.

---

## ⚙️ Execution & Setup Guide

### 1. Prerequisites
Ensure your local testing workstation has the following open-source binaries installed:
- **Apache JMeter (v5.5 or higher)**
- **SmartBear SoapUI Open-Source**
- **Bruno CLI / Desktop App**

### 2. Fetch the Infrastructure Repository
```bash
git clone https://github.com
cd Modulo02
```

### 3. Running Performance Tests (JMeter headless mode)
To execute the stress suites without GUI resource overhead, run:
```bash
jmeter -n -t "GitHub Api/your_test_plan.jmx" -l "GitHub Api/results.jtl"
```

---

## 🔐 Performance Engineering Best Practices Applied

- **Decoupled Key Management:** Dynamic test variables pass parameters via decoupled config files, keeping private auth tokens fully abstracted.
- **Headless Load Execution:** Scripts are structured for execution outside of heavy GUIs to guarantee clean local thread-pool benchmarking.
- **Granular Boundary Assertions:** Requests deploy strict response-time limits and validation parameters to accurately capture infrastructure faults.

---

## 👨‍💻 Author

**Victor Guzmán**  
*Computational Scientist | Backend Engineer | Software Quality & Test Automation Specialist*  
- 🔗 **LinkedIn:** [https://linkedin.com](https://www.linkedin.com/in/victor-h-guzm%C3%A1n-a19361187/)
