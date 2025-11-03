## ⚔️ Attack Frameworks

### 📘 Overview

To better understand and defend against cyberattacks, cybersecurity professionals use **attack frameworks** — structured models that classify, analyze, and help respond to different types and stages of attacks.  

These frameworks:
- Identify stages of an attack
- Describe attacker **tactics**, **techniques**, and **procedures (TTPs)**
- Analyze impact and intent
- Guide defensive strategy and incident response

Attack frameworks emerged in response to **advanced persistent threats (APTs)** — sophisticated, prolonged attacks involving **extended surveillance, planning, and execution**.  

> Think of these frameworks not just as theoretical models, but as **practical toolboxes** to strengthen an organization’s security posture.

Two of the most widely used frameworks are:
- **Lockheed Martin’s Cyber Kill Chain**
- **MITRE ATT&CK**

---

### 🧩 Lockheed Martin Cyber Kill Chain (2011)

The **Cyber Kill Chain** is a **seven-step model** that describes the stages of a cyberattack — from reconnaissance to data exfiltration.  

#### 🔹 1. Reconnaissance
The attacker gathers information about the target:
- Scans for vulnerabilities
- Uses open-source intelligence (OSINT) such as social media, search engines, or leaked data
- Profiles the target’s systems, users, and security posture

#### 🔹 2. Weaponization
The attacker creates or customizes a **payload** or **exploit** for delivery:
- Malware, Trojans, or viruses are crafted
- Often disguised as legitimate files (e.g., an infected Word document for phishing emails)

#### 🔹 3. Delivery
The attacker delivers the weaponized payload to the target:
- Email attachments (phishing)
- Compromised websites or drive-by downloads
- USB drops or network exploits

#### 🔹 4. Exploitation
Execution of the payload to exploit a vulnerability:
- Exploits flaws in software, OS, or configurations
- Establishes initial unauthorized access

#### 🔹 5. Installation
Persistence is established:
- Rootkits, backdoors, or remote access tools (RATs) are installed
- Ensures continued access even after detection attempts

#### 🔹 6. Command and Control (C2)
The attacker creates a communication channel:
- Connects compromised systems to a **C2 server**
- Enables remote control, lateral movement, or additional payloads

#### 🔹 7. Exfiltration
The final stage — the attacker extracts or manipulates assets:
- Data theft (financial, intellectual property, credentials)
- Launches further attacks or spreads malware internally

---

### ⚠️ Limitations of the Cyber Kill Chain

While groundbreaking, the Kill Chain model has **limitations**:

- Assumes **external threat origin** (less effective against insider threats)  
- Focuses on **traditional defense strategies** rather than adaptive or continuous ones  
- May not fully address **modern attack behaviors** like living-off-the-land or fileless attacks  

As a result, more dynamic frameworks were developed — most notably **MITRE ATT&CK**.

---

### 🧠 MITRE ATT&CK Framework (2013)

The **MITRE ATT&CK** (Adversarial Tactics, Techniques, and Common Knowledge) framework is a **comprehensive, evolving knowledge base** describing real-world adversary behavior.  

It extends beyond just attack stages — serving as a **universal language** for identifying, communicating, and mitigating cyber threats.

#### 🧱 Structure of the Framework

- Organized into a **matrix** of attacker behaviors  
- Each column represents a **tactic** (goal), and each row lists **techniques** (how that goal is achieved)

Common tactics include:
- **Initial Access**
- **Execution**
- **Persistence**
- **Privilege Escalation**
- **Defense Evasion**
- **Credential Access**
- **Discovery**
- **Lateral Movement**
- **Collection**
- **Exfiltration**
- **Command and Control**
- **Impact**

Each technique is associated with:
- Attack descriptions and real-world examples  
- Detection guidance and mitigation advice  
- Cross-references to related software and threat groups  

---

### 🌍 Benefits of MITRE ATT&CK

1. **Common Language for Security Teams**  
   - Standardizes communication about threats across organizations and vendors.

2. **Comprehensive Threat Mapping**  
   - Helps analysts correlate real incidents to known adversary TTPs.

3. **Prioritization of Defenses**  
   - Allows organizations to focus resources on the most relevant tactics and techniques.

4. **Improved Incident Response**  
   - Enables detection engineering, red-teaming, and blue-teaming using shared terminology.

5. **Adaptability**  
   - Continuously updated with new techniques observed in real-world intrusions.

---

### 🧩 Cyber Kill Chain vs MITRE ATT&CK

| Aspect | **Cyber Kill Chain** | **MITRE ATT&CK** |
|:--|:--|:--|
| **Introduced** | 2011 (Lockheed Martin) | 2013 (MITRE Corporation) |
| **Focus** | Stages of an attack (linear sequence) | Tactics, Techniques, and Procedures (TTPs) |
| **Scope** | Primarily external attacks | Both internal and external threats |
| **Goal** | Identify and stop intrusions early | Understand, detect, and mitigate adversary behavior |
| **Use Case** | Strategic defense model | Operational detection and threat hunting |
| **Update Model** | Static (7 stages) | Dynamic and continuously evolving |

---

### ✅ Summary

Attack frameworks are **essential analytical tools** in modern cybersecurity operations.  

They:
- Break down the **stages and behaviors** of cyberattacks  
- Enable organizations to **map adversary activity**  
- Provide a **shared framework** for response, mitigation, and defense improvement  

> 💡 The **Cyber Kill Chain** focuses on linear attack progression and perimeter defense,  
> while **MITRE ATT&CK** emphasizes **real-world adversary behavior** and **continuous improvement** of defenses.
