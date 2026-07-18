<div align="center">

# 👋 Hi, I'm Ravi Kiran Kambhampati

### 🛡️ Cybersecurity & CloudOps Graduate | SOC Operations | Detection Engineering | Cloud Security | GRC

Building hands-on cybersecurity projects focused on **threat detection, SIEM engineering, security monitoring, cloud security, and governance, risk & compliance**.

<br>

<a href="https://www.linkedin.com/in/ravikirankambhampati">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:ravikirankambhampati29@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<br><br>

<img src="https://img.shields.io/badge/Focus-Cybersecurity-111827?style=flat-square"/>
<img src="https://img.shields.io/badge/SOC-Operations-2563EB?style=flat-square"/>
<img src="https://img.shields.io/badge/Detection-Engineering-7C3AED?style=flat-square"/>
<img src="https://img.shields.io/badge/Cloud-Security-FF9900?style=flat-square"/>
<img src="https://img.shields.io/badge/GRC-Risk_%26_Compliance-059669?style=flat-square"/>

</div>

---

## 👨‍💻 About Me

I'm a **Cybersecurity & CloudOps graduate from York University** focused on building practical experience across **Security Operations, Detection Engineering, Cloud Security, and Governance, Risk & Compliance (GRC)**.

My hands-on work focuses on understanding and implementing the complete security monitoring lifecycle:

<div align="center">

### `Telemetry` → `Detection` → `Investigation` → `Response` → `Risk Reduction`

</div>

- 🛡️ Building hands-on **SOC and Detection Engineering** projects
- 🔎 Working with **Splunk, ELK Stack, SIEM, and security log analysis**
- ☁️ Exploring **AWS security, IAM, CloudTrail, RBAC, and least-privilege access**
- 📊 Developing **security monitoring dashboards, SPL detections, and automated alerts**
- 📋 Building practical knowledge of **GRC, NIST CSF, ISO 27001, SOC 2, and risk management**
- 🐧 Working with **Linux and Windows security telemetry**
- 🔐 Exploring **vulnerability assessment and web application security**
- 🧠 Continuously developing practical cybersecurity skills through hands-on labs and projects
- 🚀 Open to opportunities in **Cybersecurity, SOC Operations, Cloud Security, Detection Engineering, and GRC**

---

# 🚀 Featured Security Projects

## 🛡️ Enterprise SSH Threat Monitoring & Detection Engineering with Splunk

> **AWS EC2 · Splunk Enterprise · Splunk Universal Forwarder · Ubuntu · Kali Linux · SPL · Detection Engineering**

Built an end-to-end, cloud-hosted **SOC detection engineering lab** for monitoring, detecting, and investigating suspicious SSH authentication activity.

### 🔍 What I Built

- Deployed **Splunk Enterprise** as a centralized SIEM platform
- Built the lab infrastructure using **AWS EC2**
- Configured AWS networking and security groups
- Deployed the **Splunk Universal Forwarder** on a monitored Ubuntu endpoint
- Collected Linux authentication telemetry from `/var/log/auth.log`
- Centralized security events in a dedicated Splunk index
- Developed custom **SPL detection rules**
- Detected repeated SSH authentication failures
- Identified potential SSH brute-force activity
- Identified high-volume suspicious source IP addresses
- Identified frequently targeted user accounts
- Monitored successful SSH authentications
- Correlated suspicious authentication behavior
- Built an operational **SOC monitoring dashboard**
- Configured and validated **scheduled Splunk alerts**
- Developed a structured SOC investigation workflow

### 🔄 Detection Pipeline

```text
Attack Simulation
        ↓
Authentication Telemetry
        ↓
Splunk Universal Forwarder
        ↓
Splunk Enterprise
        ↓
SPL Detection Engineering
        ↓
SOC Dashboard
        ↓
Automated Alert
        ↓
SOC Investigation
