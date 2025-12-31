
# 🔐 Snort Intrusion Detection System (IDS) – Implementation & Analysis

## 📌 Overview
This project demonstrates the installation, configuration, and evaluation of **Snort as a Network Intrusion Detection System (NIDS)** in a controlled lab environment. The objective was to monitor live network traffic, detect suspicious activity, and analyze alerts generated from simulated attacks.

This project was conducted as part of a cybersecurity practical exercise for **Infotect Solutions**.

---

## 🎯 Objectives
- Install and configure Snort IDS  
- Monitor real-time network traffic  
- Generate and analyze security alerts  
- Simulate network-based attacks  
- Understand Snort rule structure and behavior  

---

## 🧪 Lab Environment
- **Operating System:** Kali Linux / Ubuntu  
- **IDS Tool:** Snort  
- **Attack Tools:** Nmap, ICMP utilities  
- **Environment:** Isolated virtual lab  

---

## ⚙️ Implementation Summary
- Installed Snort using Linux package manager  
- Configured `snort.conf` (HOME_NET, rule paths, interfaces)  
- Ran Snort in IDS mode  
- Reviewed alert logs and traffic captures  
- Validated detection using simulated attacks  

---

## 🚨 Simulated Attacks
- ICMP ping flood  
- Network and port scanning  

Snort successfully detected these activities and generated alerts with detailed metadata.

---

## 🧠 Example Snort Rule
```bash
alert icmp any any -> $HOME_NET any (msg:"ICMP Ping Detected"; sid:1000001; rev:1;)
```

---

## 📊 Key Outcomes
- Successful IDS deployment  
- Effective detection of suspicious traffic  
- Improved understanding of network security monitoring  

---

## 🏁 Conclusion
This project confirms that Snort is a reliable and effective IDS solution when properly configured. It provides practical insight into intrusion detection and alert analysis.

---

## 👤 Author
**Nana Kwame Amporful**  
Cybersecurity & Networking Professional  
CCNA | CCNP Core
