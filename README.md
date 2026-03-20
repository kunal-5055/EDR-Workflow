
# 🔐 EDR Workflow in SOC

This project explains the architecture, workflow, and role of **Endpoint Detection & Response (EDR)** in a Security Operations Center (SOC). It demonstrates how security teams detect, analyze, and respond to endpoint-based threats in real time.

---

## 📌 What is EDR?

Endpoint Detection & Response (EDR) is a cybersecurity solution that continuously monitors endpoint devices such as laptops, servers, and workstations to detect, investigate, and respond to threats.

### Key Features:
- 🔍 Continuous Monitoring (24/7 endpoint activity)
- ⚡ Real-Time Threat Detection
- 🛡️ Automated Response (isolate host, kill process)
- 🔬 Forensic Investigation (attack timeline & root cause)

---

## 🏗️ EDR Architecture

EDR consists of three main layers:

1. **Endpoints**
   - Laptops, Servers, Cloud workloads

2. **EDR Agent**
   - Collects telemetry (process, network, file activity)

3. **EDR Platform**
   - Threat detection (ML, behavioral analysis)
   - Alert generation
   - SOAR integration

---

## ⚙️ How EDR Works

1. **Collect** – Endpoint data (processes, logs, network)
2. **Detect** – Identify threats using ML & signatures
3. **Analyze** – Correlate events and map to MITRE ATT&CK
4. **Respond** – Isolate host, block IP, kill process
5. **Remediate** – Remove threat and restore system

---

## 👨‍💻 EDR in SOC (Roles)

### 🔹 SOC L1 (Triage Analyst)
- Monitor alerts
- Identify true/false positives
- Initial investigation
- Escalate incidents

### 🔹 SOC L2 (Incident Responder)
- Deep investigation
- Timeline analysis
- Containment & response

### 🔹 SOC L3 (Threat Hunter)
- Threat hunting
- Detection rule creation
- Root cause analysis

---

## 🔄 EDR Workflow (Playbook)

1. Detect → Suspicious activity identified  
2. Alert → Alert generated in EDR  
3. Triage → L1 validates alert  
4. Investigate → L2 performs deep analysis  
5. Contain → Isolate infected endpoint  
6. Eradicate → Remove malware  
7. Recover → Restore system  

---

## 🚀 Key Capabilities

- 🔎 Threat Hunting  
- 📊 MITRE ATT&CK Mapping  
- 🤖 Automated Playbooks (SOAR)  
- 🧬 Behavioral Analytics  
- 📁 Forensic Timeline  
- ☁️ Cloud & Hybrid Security  

---

## ⚔️ EDR vs Traditional Antivirus

| Feature            | Antivirus | EDR |
|-------------------|----------|-----|
| Detection         | Signature-based | Behavioral + ML |
| Zero-day Threats  | Limited  | Strong |
| Visibility        | Low      | High |
| Response          | Basic    | Advanced |
| Threat Hunting    | No       | Yes |

---

## 🎯 Key Takeaways

- EDR provides **real-time visibility** into endpoints  
- Helps SOC teams in **detection, investigation, and response**  
- Reduces response time using **automation (SOAR)**  
- Enhances security with **MITRE ATT&CK mapping**  

---

## 📄 Project Purpose

This project is designed for:
- SOC Analyst (L1) beginners  
- Cybersecurity students  
- Blue Team learners  

---


---

⭐ If you found this useful, consider giving a star!
