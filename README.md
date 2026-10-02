# Enterprise Server & Network Monitoring Platform (Zabbix)
> A comprehensive infrastructure monitoring solution built with Zabbix, Zabbix Agent, and SNMP, featuring real-time resource tracking and multi-channel alerting integrations (Telegram, Discord, and Email).

---

## Project Overview
Ensuring high availability and proactive issue detection is vital for modern data center operations. This project simulates an enterprise-grade monitoring environment to track the performance and health of virtual servers and network devices (routers) centrally, providing administrators with real-time visibility and instant notifications.

---

## Tech Stack & Tools
* **Monitoring Engine:** Zabbix Server & Zabbix Agent.
* **Network Protocol:** SNMP (Simple Network Management Protocol).
* **Virtualization & OS:** Oracle VM VirtualBox, Ubuntu Server.
* **Alerting Integrations:** Telegram Bot, Discord Webhook, Gmail SMTP.
* **Web Interface:** Zabbix Frontend (Apache, PHP, MariaDB).

---

## Architecture & Workflow
1. **Host Discovery & Configuration:** Added virtual servers and network routers into the Zabbix dashboard using appropriate templates and interfaces.
2. **Resource Monitoring (Zabbix Agent):** Continuously tracks local server metrics including CPU utilization, memory usage, storage capacity, and system service statuses.
3. **Network Monitoring (SNMP):** Collects performance metrics, interface states, and traffic bandwidth from network routers.
4. **Trigger & Multi-Channel Alerting:** Automatically fires triggers when abnormalities or *downtimes* occur, instantly dispatching notification alerts via **Telegram**, **Discord**, and **Email**.

---

## Repository Structure
```text
zabbix-infrastructure-monitoring/
├── configs/            # Sample configuration files (Zabbix Agent & SNMP settings)
├── docs/               # Architecture diagrams and system screenshots
└── README.md           # Project documentation
```
## Key Features
- **Centralized Dashboard: Real-time visibility of server resource metrics and network availability from a single interface.**
- **Hybrid Monitoring Approach: Utilizes Zabbix Agent for deep server metrics and SNMP for network device monitoring.**
- **Automated Multi-Channel Alerting: Instant problem notifications sent directly to team collaboration channels (Discord/Telegram) and email to minimize response time.**

## Author
**Salsabila Bachtiar**
- Informatics Student | Aspiring DevOps & Cloud Engineer  
[LinkedIn](https://www.linkedin.com/in/salsabila-bachtiar-30161724a) | [GitHub](https://github.com/bache1)
