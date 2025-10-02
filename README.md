# Iching-Monitoring-tolling-Tools-
🎯 Key Features
6 Interactive Tabs:

📊 Overview - System architecture, alarm flow diagram, classification matrix, and real-time statistics
🗺️ Site Map - Visual topology with device markers showing status (click markers for details)
🖥️ Devices - Complete device inventory (42 RSS + 38 TDMS) with filtering
🚨 Alarms - Live alarm log with notification channel indicators
⚙️ Simulation - Interactive scenarios for all severity levels
✅ Tests - Automated validation of system logic

Core Workflows Demonstrated:

Soft → Hard State Transition: Watch alarms progress through 3 checks (accelerated to 5 seconds)
Alarm Classification: Automatic severity assignment (Critical/Degraded/Warning/Info)
Notification Routing: Visual indicators for PagerDuty, Email, and Grafana
Business Logic: VDC pair failure detection, revenue impact assessment

Simulation Scenarios:

🔴 Critical: TSMC Ping, Database Down, UPS on Battery
🟠 Degraded: Sensor failures, Generator low fuel, VDC pairs
🟡 Warning: Statistics anomalies, Battery health
🔵 Info: Illegal communication, Config changes

Built-in Data:

13 representative devices (TSMC, TSC, UPS, VDC, Generators, DB, APP, ESXi, etc.)
Complete alarm classification rules from documentation
Real-time console-style logging
Live statistics dashboard

Everything runs offline immediately - no external dependencies, no backend required. Perfect for training, demonstrations, and understanding the monitoring system architecture!
