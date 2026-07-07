# SMART-IRRIGATION-SYSTEM-USING-LoRaWAN-and-IOT
Designed and developed a production-inspired IoT Smart Irrigation System using LoRaWAN, Raspberry Pi, cloud computing, and sensor networks to automate irrigation, reduce water consumption, support remote monitoring, and enable sustainable smart farming through long-range wireless communication

<div align="center">

<!-- Animated Header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=2ECC71&center=true&vCenter=true&width=700&lines=🌱+Smart+Irrigation+System;IoT+%2B+LoRaWAN+%2B+Cloud;Intelligent+Water+Management" alt="Typing SVG" />

<br/>

![Banner](https://img.shields.io/badge/🌾_Smart_Farming-IoT_Powered-2ECC71?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-Jan_2022_–_Jun_2022-blue?style=for-the-badge)
![Institution](https://img.shields.io/badge/VBIT-Academic_Project-orange?style=for-the-badge)

<br/>

> **Automating irrigation through real-time soil monitoring, LoRaWAN communication, and intelligent cloud-connected control.**

</div>

---

## 📌 Project Overview

A full-scale **IoT-based Smart Irrigation System** built to solve the critical agricultural challenges of **over-irrigation**, **under-irrigation**, and **inefficient water management**. The system uses **LoRaWAN long-range wireless communication** to connect distributed sensor nodes across agricultural fields to a central Raspberry Pi gateway — enabling automated, real-time, and remote irrigation control.

---

## 🚨 Problem Statement

```
❌ Over-irrigation   → Waterlogging, nutrient loss, crop damage
❌ Under-irrigation  → Crop failure, yield reduction
❌ Manual monitoring → Inefficient, labor-intensive, error-prone
❌ Water wastage     → Unsustainable agricultural practices
```

---

## ✅ Solution

```
✔ Real-time soil moisture & humidity monitoring
✔ Automated irrigation triggering via solenoid valves
✔ Long-range LoRaWAN communication across large fields
✔ Cloud connectivity for remote monitoring & control
✔ RTL-SDR spectrum analysis for signal performance
```

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    FIELD SENSOR NODES                        │
│  [Soil Moisture Sensor] + [Humidity Sensor] + [LoRa Module] │
└───────────────────────┬─────────────────────────────────────┘
                        │  LoRaWAN (Long Range, Low Power)
                        ▼
┌─────────────────────────────────────────────────────────────┐
│                  CENTRAL CONTROL STATION                     │
│         Raspberry Pi Gateway + LoRa Receiver                 │
│    [Process Data] → [Check Threshold] → [Trigger Valve]     │
└───────────────┬─────────────────────────────────────────────┘
                │                           │
                ▼                           ▼
    ┌─────────────────┐         ┌──────────────────────┐
    │  Solenoid Valve │         │    Cloud Platform     │
    │  (Auto ON/OFF)  │         │ Remote Monitor & Ctrl │
    └─────────────────┘         └──────────────────────┘
```

---

## 🛠️ Tech Stack

### 🔌 Hardware
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-Gateway-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa_Modules-Wireless_Comm-7B2FBE?style=for-the-badge)
![Sensors](https://img.shields.io/badge/Soil_%26_Humidity-Sensors-2ECC71?style=for-the-badge)
![Solenoid](https://img.shields.io/badge/Solenoid_Valve-Water_Control-E74C3C?style=for-the-badge)
![RTL-SDR](https://img.shields.io/badge/RTL--SDR_Dongle-Signal_Analysis-F39C12?style=for-the-badge)

### 💻 Software & Protocols
![LoRaWAN](https://img.shields.io/badge/LoRaWAN-Protocol-7B2FBE?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Logic_&_Control-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Cloud](https://img.shields.io/badge/Cloud-Remote_Monitoring-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-Architecture-FF6F00?style=for-the-badge)

---

## ⚙️ How It Works

```
STEP 1 — SENSE
  Sensor nodes collect soil moisture & humidity data across the field

STEP 2 — TRANSMIT
  LoRa modules send data wirelessly over long distances to Raspberry Pi

STEP 3 — PROCESS
  Raspberry Pi processes incoming data and checks threshold values

STEP 4 — DECIDE
  If moisture < threshold → Trigger solenoid valve → START irrigation
  If moisture ≥ threshold → Keep valve closed  → STOP irrigation

STEP 5 — SYNC
  Data uploaded to cloud for remote monitoring & trend analysis

STEP 6 — MONITOR
  Farmers access real-time data & control irrigation from anywhere
```

---

## 📡 LoRaWAN Communication

| Feature | Details |
|---|---|
| 📶 Range | Long-range (km-scale) across agricultural fields |
| 🔋 Power | Low-power consumption for battery-operated nodes |
| 📦 Protocol | LoRaWAN — transport-agnostic, multi-node support |
| 📻 Analysis | RTL-SDR dongle for signal & spectrum monitoring |
| 🔗 Nodes | Supports multiple sensor nodes simultaneously |

---

## 🌤️ Cloud Integration

| Feature | Details |
|---|---|
| ☁️ Data Storage | Real-time sensor data stored on cloud platform |
| 📊 Dashboard | Web-based interface for monitoring trends |
| 🌍 Remote Access | Control irrigation from anywhere via internet |
| 📈 Analytics | Analyze soil & humidity trends over time |
| 🔔 Alerts | Threshold-based notifications for farmers |

---

## 📊 Key Results

```
✅ Automated irrigation — minimized human intervention
✅ Multi-node support  — scalable for large agricultural fields
✅ Real-time monitoring — continuous environmental data collection
✅ Remote control      — internet-based access from anywhere
✅ Signal analysis     — RTL-SDR spectrum performance insights
✅ Water efficiency    — reduced wastage through intelligent control
```

---

## 🔩 Hardware Components

| Component | Role |
|---|---|
| 🖥️ Raspberry Pi | Central gateway & decision-making unit |
| 📡 LoRa Modules | Long-range wireless data transmission |
| 💧 Soil Moisture Sensor | Measures field soil water content |
| 🌡️ Humidity Sensor | Monitors atmospheric humidity levels |
| 🚰 Solenoid Valve | Controls water flow (auto ON/OFF) |
| 📻 RTL-SDR Dongle | LoRa signal monitoring & spectrum analysis |

---

## 🌾 Impact

This project demonstrates the practical power of combining **IoT**, **wireless communication**, and **cloud technologies** to transform traditional farming:

- 💧 **Reduces water wastage** through intelligent, threshold-based control
- 🌱 **Improves crop health** by maintaining optimal soil moisture
- 👨‍🌾 **Empowers farmers** with remote monitoring and control
- 📡 **Scales across large fields** using LoRaWAN multi-node architecture
- ☁️ **Enables data-driven agriculture** through cloud analytics

---

## 🎓 Academic Details

| Field | Details |
|---|---|
| 🏛️ Institution | Vignana Bharathi Institute of Technology |
| 📅 Duration | January 2022 – June 2022 |
| 🎯 Domain | IoT, Wireless Communication, Cloud Computing |
| 🛠️ Type | Academic Engineering Project |

---

<div align="center">

**Built with ❤️ for smarter, sustainable agriculture**

![IoT](https://img.shields.io/badge/IoT-🌐-2ECC71?style=flat-square)
![LoRaWAN](https://img.shields.io/badge/LoRaWAN-📡-7B2FBE?style=flat-square)
![Cloud](https://img.shields.io/badge/Cloud-☁️-4285F4?style=flat-square)
![Agriculture](https://img.shields.io/badge/Smart_Farming-🌾-F39C12?style=flat-square)

</div>
