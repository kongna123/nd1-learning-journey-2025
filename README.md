# 🏠 IoT Home Automation Learning Platform

Welcome to the comprehensive Docker-based IoT learning environment. This project integrates Python programming with real-world IoT services to teach the full stack of Internet of Things development.

## 📖 Overview

This platform provides a complete ecosystem for learning and prototyping IoT solutions without needing physical hardware initially. It uses **Docker** to orchestrate essential services and **Python** for logic   and simulation.

**Core Stack:**

- **Message Broker:** EMQX (MQTT)
- **Backend Logic:** Python (Flask) & Node-RED
- **Database:** InfluxDB (Time-series)
- **Visualization:** Grafana & FlowFuse
- **Simulation:** Custom Python IoT Simulator

---

## 📚 Learning Modules (Knowledge Base)

Select a topic below to explore detailed concepts and implementation notes:

### 🌐 [1. IoT Concepts & Architecture](./docs/IoT_Concepts.md)

> Understanding the full-stack IoT architecture, data flow, and system integration strategies used in this project.

### 🤖 [2. Embedded Systems](./docs/Embedded_Systems.md)

> Deep dive into device simulation, hardware logic, sensors, actuators, and home automation rules.

### 📡 [3. Communication & Networking](./docs/Communication_Networking.md)

> Protocols (MQTT, HTTP), API development, and Docker internal networking/routing.

### 💻 [4. Software & Programming](./docs/Software_Programming.md)

> The tech stack: Python scripting, Docker containerization, InfluxDB queries (Flux), and visualization tools.

### 🚀 [5. Future Works & Projects](./docs/Future_Works_Projects.md)

> Ideas for extending the project, AI integration, hardware implementation, and roadmap.

---

## 🛠 Quick Service Reference

Once the Docker environment is running, access the services here:

| Service            | Local Address            | Default Creds    |
| :----------------- | :----------------------- | :--------------- |
| **Node-RED**       | `http://localhost:1880`  | -                |
| **Grafana**        | `http://localhost:3000`  | `admin`/`admin`  |
| **EMQX Dashboard** | `http://localhost:18083` | `admin`/`public` |
| **Flask API**      | `http://localhost:5000`  | -                |

---

> **Note:** To view the linked files properly in VS Code, ensure all `.md` files are located in the same directory as this README, or update the links accordingly.
