## ⚠️ Cybersecurity Threats

### What is a cybersecurity threat?
A **cybersecurity threat** is an action that exploits a vulnerability and results in harm to a network or computer system. **Bad actors** instigate threats and use various **attack vectors** (methods) to achieve their goals. An attack vector consists of three components:

1. **Vulnerability** — the weakness being exploited (e.g., a user, an unpatched system).  
2. **Mechanism (object)** — the tool or technique that exploits the vulnerability (e.g., malware, social engineering message).  
3. **Pathway** — the channel used to deliver the mechanism to the vulnerability (e.g., email, USB, physical access).

---

### 🧩 Examples (illustrating the three components)

**Example 1 — Phishing / Malware via Email**
- Vulnerability: the user (trusting, clicks attachments)  
- Mechanism: malware hidden in an attached document + socially engineered message  
- Pathway: email

**Example 2 — Physical Social Engineering + USB Malware**
- Vulnerability: authorized person (trusting) and an unprotected server  
- Mechanism: malware on a USB device; convincing pretext to gain access  
- Pathway: physical entry (door) and USB port

These examples show attack vectors can be electronic social engineering, physical social engineering, or technical (e.g., misconfiguration). Multiple vectors are often chained together to form an **attack path**.

---

### 🔗 Attack Path
An **attack path** is the chain of events that occurs when attack vectors are exploited in sequence (preparation → foothold → lateral movement → data exfiltration or disruption).

```mermaid
graph TD
    A[🧭 Initial Vector] --> B[💥 Exploit Vulnerability]
    B --> C[🪜 Foothold Established]
    C --> D[🔄 Lateral Movement]
    D --> E[🎯 Objective Achieved — (data exfiltration / disruption)]

    classDef stage fill:#007BFF,stroke:#004085,color:#fff,stroke-width:1.5px,rx:6,ry:6;
    classDef final fill:#28A745,stroke:#155724,color:#fff,stroke-width:1.5px,rx:6,ry:6;

    class A,B,C,D stage;
    class E final;

```

---

## 🗂️ Major Categories of Cybersecurity Threats

Cybersecurity threats can be broadly grouped into four categories:

- **Social Engineering** — Psychological manipulation to trick people into actions that compromise security (e.g., phishing, vishing, smishing).  
- **Malicious Software (Malware)** — Software designed to disrupt, damage, or gain unauthorized access (e.g., ransomware, Trojans, worms).  
- **Unauthorized Access (Physical or Digital)** — Tailgating into restricted areas, shoulder surfing, credential theft.  
- **System Design Failure** — Security flaws or misconfigurations in systems/applications exploited by attackers.

---

## 🔎 Common Attack Methods & How They Fit

- **Phishing** — Email-based social engineering to harvest credentials or deliver malware.  
  - *Spear phishing*: Targeted at a specific individual or group.  
  - *Whale phishing*: Aimed at high-value individuals (CEOs, CFOs).  

- **Trojan Horse** — Malware disguised as a legitimate file or program; often used to gain a foothold.  

- **Ransomware** — Encrypts or blocks access to systems/data until a ransom is paid.  

- **DDoS (Distributed Denial-of-Service)** — Botnet-driven flood of requests that overwhelms a target, causing denial of service.  
  > 📝 **Note:** DDoS often requires prior infection of many machines (frequently via phishing).

- **Zero-Day Exploit** — Attacker uses an unknown vulnerability (vendor has zero days to patch).  

- **Birthday Attack** — Cryptographic attack exploiting weaknesses in hashing algorithms.  

- **Brute Force Attack** — Systematically tries credentials until success; effective against weak passwords.  

- **Social Engineering (Physical)** — Tailgating, impersonation, or tricking personnel into granting access.

---

## 🧠 Pre-Exploit vs Post-Exploit

| Stage | Description | Examples |
|--------|--------------|-----------|
| **Pre-Exploit Vectors** | Methods used to gain initial access. | Phishing, brute force, exploiting vulnerabilities |
| **Post-Exploit Vectors** | Actions taken after compromise to achieve goals. | Lateral movement, DDoS, data exfiltration, ransomware deployment |

---

## 🛡️ Defensive Considerations (High Level)

- **User Education** — Train people to recognize phishing and social engineering attempts.  
- **Strong Authentication & Least Privilege** — Reduce attack surface and limit compromised account impact.  
- **Patch Management** — Regularly update systems to mitigate zero-day and known vulnerabilities.  
- **Backups & Recovery** — Protect backups offline to defend against ransomware.  
- **Monitoring & Detection** — Identify anomalous activity (e.g., botnet participation, credential misuse).  
- **Physical Security Controls** — Prevent tailgating and unauthorized access to restricted areas.  
- **Security by Design** — Build and maintain systems to minimize misconfigurations and design flaws.

---

## ✅ Summary

Attack vectors are **methods** that exploit **vulnerabilities** through a specific **mechanism** and **pathway**.  
Threat actors combine these vectors to form **attack paths** that accomplish malicious goals.

> 🧩 **Effective defense** requires a layered approach — integrating technology, process, and people to detect, prevent, and respond to attacks across all stages.
