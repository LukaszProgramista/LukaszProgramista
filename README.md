<h1 align="center">👋 Hi, I'm Łukasz Głowacki</h1>
<h3 align="center">.NET Developer • Mobile & Web Engineer • DevOps Enthusiast • Team Lead</h3>

<p align="center">
  <a href="https://github.com/LukaszProgramista">
    <img src="https://komarev.com/ghpvc/?username=LukaszProgramista&color=brightgreen" />
  </a>
</p>

---

## 🌟 About Me

I’m a passionate **.NET Developer & Team Lead from Poland**, working with modern technologies across **mobile, cloud, backend, DevOps**, and **research-grade engineering**.

I love building **clean, scalable, maintainable systems**, combining software with electronics, and working on both **industry-grade applications** and **deep technical research projects**.  
My interests span mobile development, embedded systems, underwater acoustics, and cloud architecture.

---

## 🚀 What I'm Working On

- 🧭 **Underwater Acoustic Communication System for Divers** — Master’s Thesis Project  
- 🗄️ **StoreIT! — Virtual Cabinet** (Blazor + MAUI)  
- 🏠 **Smart Home Simulator** (React + TypeScript + SVG)  
- 🌊 **WhaleDiver** — Dive physics & visualization app (MAUI)  
- 🐳 **Dockerized backend & cloud services** (AWS EC2, S3, Nginx)

---

## 📘 What I'm Learning

- Advanced AWS architecture  
- Distributed & resilient backend systems  
- Underwater acoustic communication  
- MAUI UI/UX performance  
- OWASP Top 10 for .NET applications  

---

# 🔧 Featured Projects

Below are the key projects I develop at home and as part of my academic work.

---

## 🧭 Underwater Communication System for Divers  
**Master’s Thesis Project — 2025**

A research-driven prototype of an **acoustic communication system** allowing divers to exchange short messages underwater.  
The project focuses on evaluating the feasibility of **low-cost underwater communication** for improving diver safety.

### ✨ Key Components

#### 📱 Mobile Application (Android, .NET MAUI)
- Sends predefined short messages  
- Displays depth, temperature, and dive time  
- Communicates with the hardware module via USB  

#### 🔧 Hardware Module
- Seeeduino XIAO (SAMD21 / RP2040)  
- Piezoelectric transducer (25–40 kHz)  
- Hydrophone + low-noise preamp  
- Band-pass filter  
- DRV8251 / DRV8872 half-bridge driver  
- MS5837 depth/pressure sensor  
- Li-ion battery + charger  
- Waterproof 3D-printed housing  

#### 🧪 Testing Environments
- Dry tests  
- Bathtub tests  
- Pool tests (1–5 m)  
- Open-water dives (up to 20 m)

### 🧠 Software Architecture
- Firmware: **C / C++**  
- Mobile: **.NET MAUI**  
- Optional backend: **ASP.NET Core** (log storage & analysis)  

### 📊 Expected Results
- Reliable range in air/pool/open water  
- Impact of depth, obstacles & orientation  
- Transmission success rate & latency  
- Practicality for diver safety  

---

## 🏠 Smart Home Simulator (SmartBuildingSimulator)

An interactive **top-down smart home simulation** built in **React + TypeScript**, using **Konva/SVG** to render building layouts.

It serves as a local digital twin of a real apartment — designed not only for simulation, but also for **AI-driven automation research**.

### ✨ Features
- Real-time room lighting simulation  
- Interactive floor plan  
- Expandable automation engine  
- IoT-ready architecture  
- **AI/ML-driven home automation (see below)**  

---

## 🤖 **Machine Learning Automation (ML.NET + Home Assistant Data)**

One of the core research components of this project involves training a **.NET ML model** based on historical data exported from **Home Assistant**.

The goal is to let the model **learn daily routines**, **predict device states**, and eventually **control the virtual smart home autonomously**.

### 🔍 Data Sources (from Home Assistant)
- Light usage patterns (time, room, brightness levels)  
- Temperature changes & thermostat actions  
- Sensor activity (motion, presence, door sensors)  
- Device on/off schedule  
- Sun elevation / time-of-day context  
- User-triggered automation events  

### 🧠 ML Workflow
1. **Export Home Assistant history** (CSV / Influx / API).  
2. Preprocess behavioral data (normalization, smoothing, context windows).  
3. Train ML.NET models:  
   - **Classification** → predict if a device should turn ON/OFF  
   - **Regression** → predict brightness/temperature levels  
4. Validate on real sequences from Home Assistant.  
5. Integrate predictions into Smart Home Simulator engine.  
6. The simulator uses the model to **act as an AI home controller**.

### 🌐 Result
The Smart Home Simulator becomes an **AI-powered digital twin** that:  
- Predicts user behavior  
- Optimizes lighting/temperature  
- Reacts dynamically to simulated sensors  
- Can generate new automation rules  
- Works even without the real Home Assistant system  

This transforms the simulator from a visual tool into a **research platform for autonomous smart homes**.

---

## 🛠 Tech Stack
- React + TypeScript  
- react-konva / SVG  
- Custom automation engine  
- **ML.NET**  
- **Home Assistant API / CSV exports**  
- .NET backend for model training
  
---

## 🗄️ StoreIT! — Virtual Cabinet

A modern **document organization system** inspired by real shelves and drawers.  
Built for both **web (Blazor)** and **mobile (MAUI)**.

### ✨ Features
- Visual “shelf & drawer” UX  
- Metadata-based search  
- Cloud integrations (REST, Google Drive, AWS)  
- Offline-first design  
- Auto-sync  

### 🛠 Tech Stack
- Blazor (WebAssembly/Server)  
- MAUI  
- .NET 7/8  
- REST API backend  

---

## 🌊 WhaleDiver — Depth Visualizer & Dive Physics

A **.NET MAUI application** simulating underwater depth, pressure, colors, and dive parameters.

### ✨ Features
- Depth slider (-200 m to 0 m)  
- Real physics-based pressure calculations  
- Water-color depth gradient  
- REST API integration  
- Persistent demo license  

### 🛠 Tech Stack
- .NET MAUI  
- MVVM  
- Custom animation pipeline  
- Secure Storage  
- REST API backend  

---

# 🛠 Tech Stack Overview

### 💻 Backend & Core
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp)
![ASP.NET](https://img.shields.io/badge/ASP.NET-5C2D91?style=for-the-badge&logo=dotnet)
![EF Core](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge)

### 📱 Mobile
![MAUI](https://img.shields.io/badge/.NET%20MAUI-512BD4?style=for-the-badge&logo=dotnet)
![Xamarin](https://img.shields.io/badge/Xamarin-3498DB?style=for-the-badge)

### 🌐 Frontend
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge)
![Vue.js](https://img.shields.io/badge/Vue.js-41B883?style=for-the-badge&logo=vuedotjs)

### 🐳 DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws)

---

# 📊 GitHub Stats

<p align="center">
  <img width="46%" src="https://github-readme-stats.vercel.app/api?username=LukaszProgramista&show_icons=true&theme=tokyonight" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=LukaszProgramista&theme=tokyonight"/>
</p>

---

# 📫 Contact

- 📧 Email: **lukaszglowacki112@gmail.com**  
- 🔗 LinkedIn: **https://www.linkedin.com/in/lukasz-glowacki-177b96185/**  
- 🌍 GitHub: **https://github.com/LukaszProgramista**

<p align="center">
  <em>Thanks for visiting my profile — stay curious & keep building 🔥</em>
</p>
