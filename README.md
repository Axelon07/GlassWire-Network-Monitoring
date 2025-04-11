# GlassWire - Windows Network Monitoring Tool

## 📌 Overview
GlassWire is a free Windows network monitoring tool that shows live traffic, detects new connections, and alerts users of suspicious activity. This project uses GlassWire to demonstrate network surveillance, anomaly detection, and simulated intrusion response.

## 🖥️ Installation (Windows)
1. Download from: https://www.glasswire.com/download/
2. Run the installer and follow the default setup
3. Launch GlassWire – monitoring begins automatically

## ⚙️ Configuration Snapshot
- Alerts: Enabled for new devices and app network activity
- Graph Interval: Real-time mode
- Monitored Apps: Chrome, Discord, Zoom, System processes
- Network View: Local device and subnet scanning

## 🧪 Simulated Use Case
To demonstrate anomaly detection:
1. Installed Angry IP Scanner on a second device in the same network
2. Scanned the local subnet: `192.168.1.1 - 192.168.1.255`
3. GlassWire on the primary device generated an alert:
   - “New Device Connected”
   - Included IP, MAC address, and hostname

This simulates basic reconnaissance behavior (network scan).

## 📂 Project Files
- `glasswire-settings.txt` – Manual config snapshot
- `simulate-threat.txt` – Steps to simulate a network scan
- `document-findings.txt` – Full docs explaining issues and project findings
- `screenshots/` – Contains UI views (graph, alert, etc.)

## 📸 Screenshots
![Network Graph](screenshots/graph.png)
![Alert Popup](screenshots/alerts.png)
![Apps](screenshots/apps.png)
![Activity Review](screenshots/activity.png)
![Logs](screenshots/logs.png)

## 🛡️ How It Relates to Cybersecurity
This tool aligns with core topics from the course:
- Network monitoring
- Threat detection
- Intrusion simulation
- Basic firewall management (via Windows Firewall)

## 🧠 Note
Some features like full firewall control are only available in the Pro version, but this project uses only the free version to keep it accessible.

---
