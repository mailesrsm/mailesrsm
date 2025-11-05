<!-- Profile: mailesrsm | Hybrid visual README (icons + color, clean layout) -->

<div align="center">

# **Maileswaran R S**
**IoT Systems · Embedded Hardware · Cloud Integrations**  
_“Turning sensor signals into real-time, actionable data.”_

[![GitHub Followers](https://img.shields.io/github/followers/mailesrsm?label=Followers&style=flat-square)](https://github.com/mailesrsm)
[![Profile Views](https://komarev.com/ghpvc/?username=mailesrsm&style=flat-square)](https://github.com/mailesrsm)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maileswaran%20Srinivasan-blue?logo=linkedin&style=flat-square)](https://linkedin.com/in/maileswaran-srinivasan)
[![Mail](https://img.shields.io/badge/Email-maileswaranrs%40gmail.com-red?logo=gmail&style=flat-square)](mailto:maileswaranrs@gmail.com)

</div>

---

## 🚀 Now
- Building **Smart Pothole Detection & Reporting System**
- **MPU6050 + GPS** on **ESP32/NodeMCU** → **Firebase RTDB** via **Cloudflare Workers**
- Real-time dashboard & alerts

---

## 🧠 Core Strength
**End-to-end pipeline:** Sensor ➜ Microcontroller ➜ Transmission ➜ Cloud DB ➜ Dashboard ➜ Alerts  
I don’t stack-dump; I **ship systems that run**.

---

## 🛠️ Tech I Actually Use

### Hardware & Modules
<p>
  <img height="28" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" alt="Arduino"/>
  <img height="28" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C/C++"/>
  <img height="28" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python"/>
</p>

![ESP32](https://img.shields.io/badge/ESP32-333?style=flat-square)
![NodeMCU](https://img.shields.io/badge/NodeMCU-333?style=flat-square)
![MPU6050](https://img.shields.io/badge/MPU6050-333?style=flat-square)
![GPS](https://img.shields.io/badge/GPS-333?style=flat-square)
![GSM](https://img.shields.io/badge/GSM-333?style=flat-square)

### Cloud & Backend
<p>
  <img height="28" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" alt="Firebase"/>
  <img height="28" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cloudflare/cloudflare-original.svg" alt="Cloudflare"/>
  <img height="28" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git"/>
</p>

![Firebase RTDB](https://img.shields.io/badge/Firebase%20RTDB-FFCA28?logo=firebase&logoColor=000&style=flat-square)
![Auth](https://img.shields.io/badge/Firebase%20Auth-FFCA28?logo=firebase&logoColor=000&style=flat-square)
![Storage](https://img.shields.io/badge/Firebase%20Storage-FFCA28?logo=firebase&logoColor=000&style=flat-square)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?logo=cloudflare&logoColor=fff&style=flat-square)
![Flask API](https://img.shields.io/badge/Flask%20API-000?logo=flask&style=flat-square)

### Frontend (Lite)
<p>
  <img height="26" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML"/>
  <img height="26" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS"/>
  <img height="26" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JS"/>
</p>

![Dashboards](https://img.shields.io/badge/Realtime%20Dashboards-0A66C2?style=flat-square)
![Maps](https://img.shields.io/badge/Map%20Visualizations-0A66C2?style=flat-square)

---

## 🛰️ Featured Build — Smart Pothole Detection
**Goal:** Detect road anomalies, classify severity, geotag, and notify maintenance teams in real time.

```mermaid
flowchart LR
  A[MPU6050 + GPS] --> B[ESP32/NodeMCU FW]
  B --> C[Flask/HTTP]
  C --> D[Cloudflare Worker]
  D --> E[Firebase RTDB]
  E --> F[Live Dashboard / Alerts]
