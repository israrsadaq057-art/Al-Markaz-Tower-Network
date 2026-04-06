# 🏢 Al-Markaz Tower - Complete FTTH & Security Network Design

<div align="center">

![Network Status](https://img.shields.io/badge/Network-Design-blue)
![FTTH](https://img.shields.io/badge/FTTH-GPON-green)
![Security](https://img.shields.io/badge/Security-24x7-red)
![Cisco](https://img.shields.io/badge/Cisco-Networking-blue)
![Hikvision](https://img.shields.io/badge/Hikvision-4K-yellow)

### 📍 Blue Area, Islamabad, Pakistan

**A Production-Ready Network Design for a 5-Floor Residential Tower**

</div>

---

## 📋 Project Overview

| Aspect | Details |
|--------|---------|
| **Building Name** | Al-Markaz Tower |
| **Location** | Blue Area, Islamabad, Pakistan |
| **Floors** | 5 + Basement Parking |
| **Apartments** | 20 (4 per floor) |
| **Total Residents** | 100+ People |


---

## 🌐 VLAN Configuration

| VLAN ID | Name | Subnet | Gateway | Purpose |
|---------|------|--------|---------|---------|
| **10** | Management | 10.10.10.0/24 | 10.10.10.1 | Network Device Management |
| **20** | CCTV | 10.10.20.0/24 | 10.10.20.1 | Security Cameras (24) |
| **30** | WiFi-Common | 10.10.30.0/24 | 10.10.30.1 | Lobby & Community Hall |
| **40** | Apartments | 10.10.40.0/21 | 10.10.40.1 | 20 Apartments |
| **50** | VoIP | 10.10.50.0/24 | 10.10.50.1 | Intercom System |
| **60** | NVR | 10.10.60.0/24 | 10.10.60.1 | Video Storage |

---

## 📷 Security Camera Placement

| Floor | Camera IDs | Type | Coverage |
|-------|------------|------|----------|
| **Basement** | CAM-01 to CAM-06 | Bullet + Dome 360° | Entry/Exit Ramps, Parking Rows A/B/C, MDF Door |
| **Floor 1** | CAM-07 to CAM-11 | Bullet + Dome 360° | Main Entrance, Reception, Elevator, Stairs, Back Entrance |
| **Floor 2** | CAM-12, CAM-13 | Dome 4K + Dome 360° | Elevator Lobby, Main Corridor |
| **Floor 3** | CAM-14, CAM-15 | Dome 4K + Dome 360° | Elevator Lobby, Main Corridor |
| **Floor 4** | CAM-16, CAM-17 | Dome 4K + Dome 360° | Elevator Lobby, Main Corridor |
| **Floor 5** | CAM-18, CAM-19, CAM-20 | Dome 4K + Dome 360° + Bullet | Elevator Lobby, Main Corridor, Rooftop Door |

**Total: 24 Cameras | 4K Resolution | Night Vision | 30-Day Retention**

---

## 🛠️ Equipment List

### FTTH Equipment (Basement MDF)
| Device | Model | Quantity |
|--------|-------|----------|
| GPON OLT | Nokia 7360 ISAM FX-8 | 1 |
| GPON ONT | Nokia G-240W-F | 20 |
| 1:32 Splitter | GPON PLC | 2 |
| Fiber Patch Panel | 24-port SC/APC | 2 |

### Network Equipment
| Device | Model | Quantity |
|--------|-------|----------|
| Firewall | Cisco Firepower 2130 | 1 |
| Core Switch | Cisco Catalyst 9300-48P | 1 |
| Distribution Switch | Cisco Catalyst 9200-24P | 5 |
| WiFi 6 Router | Cisco 9130AXI | 20 |
| WiFi AP | Cisco 9130AXI | 6 |
| PoE Switch | Hikvision 24-port | 2 |

### Security Equipment
| Device | Model | Quantity |
|--------|-------|----------|
| NVR | Hikvision 64-Channel | 1 |
| 4K Dome Camera | Hikvision DS-2CD2386G2 | 20 |
| 4K Bullet Camera | Hikvision DS-2CD2T86G2 | 4 |
| 8TB HDD | WD Purple | 8 |

### Power Backup
| Device | Model | Quantity |
|--------|-------|----------|
| UPS | APC 6kVA | 2 |
| Generator | 20kVA Diesel | 1 |
| ATS Panel | Automatic Transfer Switch | 1 |

---

## 💰 Project Budget

| Category | Cost (USD) | Cost (PKR) |
|----------|------------|------------|
| FTTH Equipment | $8,370 | ₨ 2,343,600 |
| Network Equipment | $59,410 | ₨ 16,634,800 |
| Security Equipment | $9,400 | ₨ 2,632,000 |
| Power Backup | $17,900 | ₨ 5,012,000 |
| **Equipment Subtotal** | **$95,080** | **₨ 26,622,400** |
| Labor & Services | $15,000 | ₨ 4,200,000 |
| Contingency (10%) | $11,008 | ₨ 3,082,240 |
| **GRAND TOTAL** | **$121,088** | **₨ 33,904,640** |

### Monthly Operational Costs
| Item | Cost (USD) | Cost (PKR) |
|------|------------|------------|
| ISP Bandwidth (1 Gbps) | $500 | ₨ 140,000 |
| Electricity | $300 | ₨ 84,000 |
| Maintenance Contract | $400 | ₨ 112,000 |
| Security Guard (24/7) | $600 | ₨ 168,000 |
| Generator Fuel | $150 | ₨ 42,000 |
| **Total Monthly** | **$1,950** | **₨ 546,000** |

---

## 📁 Project Structure

```

Al-Markaz-Tower-Network/
│
├── 📁 diagrams/ # Network Diagram
│ └── complete-network.html # Interactive network diagram
│
├── 📁 documentation/ # Project Documentation
│ └── complete-project-documentation.html # 7-tab comprehensive docs
│
├── 📁 floor-plans-detailed/ # Interactive Floor Plans
│ └── complete-floor-plans.html # 6 floors with camera positions
│
├── 📁 floor-plans-pdf/ # Printable Floor Plans
│ ├── 01-basement-floor-plan.html # Basement (6 cameras)
│ └── 02-floor-1-plan.html # Floor 1 (5 cameras)
│
├── 📁 monitoring/ # Network Monitoring
│ └── network-monitoring-dashboard.html # Real-time dashboard
│
├── 📁 configurations/ # Device Configurations
│ ├── 01-firewall-config.txt # Cisco Firepower 2130
│ ├── 02-core-switch-config.txt # Cisco Catalyst 9300
│ ├── 03-olt-config.txt # Nokia 7360 ISAM FX
│ ├── 04-distribution-switch-floor1.txt # Cisco Catalyst 9200
│ ├── 05-apartment-router-5a.txt # Cisco 9130AXI WiFi 6
│ └── 06-nvr-config.txt # Hikvision 64-Channel
│
├── 📁 cabling-schedule/ # Cabling Details
│ ├── 01-fiber-cabling-schedule.html # Fiber optic cabling
│ └── 02-ethernet-cabling-schedule.html # Cat6 ethernet cabling
│
├── 📁 excel-sheets/ # Data Files
│ ├── 01-equipment-inventory.csv # 50+ devices with serials
│ ├── 02-ip-assignment-sheet.csv # Complete IP addressing
│ ├── 03-apartment-wifi-credentials.csv # WiFi details per apt
│ └── 04-cabling-matrix.csv # Cable connection matrix
│
└── 📁 qr-labels/ # QR Code Labels
└── qr-labels-generator.html # 61 printable QR codes
├── rack-layouts/
│   ├── 01-mdf-rack-layout.html
│   └── 02-floor-distribution-rack.html

```

# 👋 Hi, I'm Israr Sadaq

<div align="center">
  
[![CCNA](https://img.shields.io/badge/CCNA-Certified-1BA0D7?logo=cisco)](https://www.cisco.com)
[![CCNP](https://img.shields.io/badge/CCNP-Certified-1BA0D7?logo=cisco)](https://www.cisco.com)
[![Network Engineer](https://img.shields.io/badge/Network-Engineer-blue)](https://github.com/israrsadaq057-art)

</div>

## 🧑‍💻 About Me

I'm a **Certified Network Engineer** (CCNA | CCNP) based in **Berlin, Germany**, specializing in:

- 🔹 **Enterprise Network Design & Implementation**
- 🔹 **FTTH / GPON Network Architecture**
- 🔹 **Cisco Routing & Switching**
- 🔹 **Network Security (Firewalls, VPNs, ACLs)**
- 🔹 **Surveillance Systems (IP Cameras, NVR)**
- 🔹 **Fiber Optic Network Planning**

---

## 🏢 Featured Project: Al-Markaz Tower

**Complete FTTH + Security Network Design for a 5-Floor Residential Tower**

| Aspect | Details |
|--------|---------|
| 📍 Location | Blue Area, Islamabad, Pakistan |
| 🏗️ Building | 5 Floors + Basement (20 Apartments) |
| 📡 Technology | GPON FTTH (Nokia OLT + 20 ONTs) |
| 🔥 Security | 24 x 4K Hikvision Cameras |
| 🌐 Network | Cisco Catalyst Switching |
| 📊 Budget | $121,088 USD |

 
