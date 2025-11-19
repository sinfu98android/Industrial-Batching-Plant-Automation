# Orchestrix---BatchingPlant
A lightweight industrial orchestration module for batching automation, real-time analytics, and direct PLC integration. Designed for high-speed, low-latency environments without requiring middleware servers or OPC bridges.<br>
**Designed and developed the Orchestrix software framework entirely from scratch**. Applied it to a refurbished batching plant, collaborating with the operator and their staff for system integration, commissioning, and performance optimization<br>

### 🏗 System Architecture

Frontend (Web UI) <br>
  ↓ <br>
Backend (PHP + C/C++ Runtime) <br>
   ↓ <br>
Memcache (Queue + Cache Layer) <br>
   ↓ <br>
MySQL Database <br>
   ↓ <br>
PLC / Load Cell Devices <br>

**Network & Protocol Support** <br>
•	TCP / RS485 <br>
•	Local network or cloud-based control <br>
•	No OPC server required <br>

### ⚙️ Tech Stack <br>
•	Frontend: JavaScript web UI <br>
•	Backend: PHP <br>
•	Low-Level Drivers: Custom C/C++<br>
•	Caching/Queue: Memcache <br>
•	Database: MySQL <br>
•	Deployment: FTP (WinSCP – legacy industrial environments) <br>


### 🚀 Batching Plant Features 
**Core Features** <br>
•	ERP → Automatic batching job creation <br>
•	Real-time ingredient weighing <br>
•	Automatic sequence control (mixing, dosing, loading) <br>
•	Load cell amplifier integration <br>
•	Remote I/O & PLC command execution <br>
•	Real-time runtime logging <br>
•	Event monitoring + alarms <br>
•	Full traceability (batch history) <br>

**Operational Features** <br>
•	Multi-plant centralized web control <br>
•	1 operator can run multiple batching lines <br>
•	Remote troubleshooting & maintenance <br>
•	Brand-agnostic hardware support <br>
•	Very lightweight (no middleware bridge needed) <br>


### ⚡ Performance & Impact <br> 
•	2+ years continuous operation in real industrial environment <br>
•	Reduced downtime via predictive maintenance <br>
•	OEE insights for cycle time, machine utilization, quality <br>
•	Faster troubleshooting with centralized logs <br>
•	Reduced staffing → 1 operator can handle multi batching plant <br>
•	Seamless remote access lowers onsite technician visits <br>

### 📊 Data Intelligence & Analytics <br>
**Orchestrix generates:** <br>
•	Material accuracy variance <br>
•	Cycle time distribution <br>
•	Batch quality metrics <br>
•	Equipment error patterns <br>
•	Predictive failure alerts<br>
•	Production volume summaries <br>
•	Capable of weighing operations without job order <br>
•	Minimizes material corruption and theft <br> 
•	Provides deep analysis and historical quality records for batching plant performance <br>


### 🧩 PLC Edge Integration <br>
**Orchestrix communicates directly with:** <br>
•	Mitsubishi PLCs <br>
•	Omron PLCs <br>
•	Schneider PLCs (Modbus) <br>
•	Modbus TCP devices <br>
•	Load cell amplifiers <br>
**This allows:** <br>
•	Fast message response <br>
•	Custom low-level C/C++ driver handling <br>
•	No OPC server required <br>
•	High performance in constrained environments <br>

### 👨‍💻 Author Contribution <br>
This system and all components described in this document—including the architecture, PLC protocol implementation, runtime modules, backend services, data intelligence layer, and on-site commissioning—were fully designed and developed by the author. <br><br>
 
### Technical Batching Plant pdf
[📎  download technical pdf](https://github.com/sinfu98android/Orchestrix_BatchingPlant/blob/b4af02769f587b4d781dcbac984bf1c218ffe177/Batching%20plant%20Github.pdf)   <br>
*Note : Github Sometimes cannot preview PDF file directly, please download to view.*
<br><br>

### Watch a video of the **commissioning and on-site trial** of the Batching Plant system
[📹  Batching Plant system video](https://youtu.be/asrHC0f4MmY?si=lkpU2SrsDjZ1knN6) <br>

### This Batching Plant system is built on top of the Orchestrix framework <br>
[🔗  Orchestrix Framework link](https://github.com/sinfu98android/Orchestrix_main_framework) 
Check it out!
