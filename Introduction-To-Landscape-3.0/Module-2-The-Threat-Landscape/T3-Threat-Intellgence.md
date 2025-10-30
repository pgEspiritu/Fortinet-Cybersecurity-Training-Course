## 🧠 Threat Intelligence

### 📖 Definition

According to **Gartner**,  
> *“Threat intelligence is evidence-based knowledge, including context, mechanisms, indicators, implications, and actionable advice, about an existing or emerging menace or hazard to assets that can be used to inform decisions regarding the subject's response to that menace or hazard.”*

This definition highlights **three key characteristics** of threat intelligence:

- **Relevant**  
- **Actionable**  
- **Contextual**

---

### 🎯 Characteristics of Threat Intelligence

#### 1. Relevance
Threat intelligence must be **relevant** to your organization.  
- Example: A macOS vulnerability report is irrelevant if your company does not use Apple devices.  
- Relevance depends on your **environment**, **assets**, and **business sector**.

#### 2. Actionability
Threat intelligence must provide enough information for **defensive action**.  
- Example: Knowing that *Dynamite Panda* targets hospitals is informative — but unless you know **how** they attack, you cannot take action.  
- Actionable intelligence includes **specific indicators**, **attack vectors**, and **mitigation steps**.

#### 3. Context
Threat intelligence must include **context** — details that help assess the **actual risk** to your environment.  
- Example: Knowing you have no macOS devices on your network makes a macOS vulnerability irrelevant.  
- Context turns **raw data** into **intelligence**.

> Many pieces of information alone are not threat intelligence — but when combined with additional relevant context, they become valuable intelligence.

---

### 🌐 Sources of Threat Intelligence

#### 🏢 Internal Sources
Information gathered from your own organization’s IT and security operations:
- Server logs & network device logs  
- Past incident reports  
- Captured network traffic  
- Penetration test results  
- SIEM alerts and baseline data  

These internal datasets are organized and analyzed into **relevant, actionable, and contextual intelligence**.

#### 🌍 External Sources
External threat intelligence is available from **government**, **private**, and **open-source** entities.

##### Government Sources
- **DHS (Department of Homeland Security)**  
- **FBI (Federal Bureau of Investigation)**  
- **NIST (National Institute of Standards and Technology)**  

> These typically provide guidance, threat trends, and best practices, not malware-specific data.

##### Private & Industry Sources
- **SANS Institute**  
- **FortiGuard (Fortinet Threat Intelligence Service)** — offers both free and subscription-based intelligence.  
  - Details malware behaviors  
  - Rates severity of threats to help prioritize defenses

##### Open-Source Intelligence (OSINT)
Free and community-driven intelligence sources:
- **CVSS (Common Vulnerability Scoring System)** — rates vulnerability severity from **0–10** based on:
  - Exploitability  
  - Impact  
  - Mitigation effectiveness  
- **MITRE ATT&CK** — knowledge base of **adversary tactics, techniques, and procedures (TTPs)**.  
- **Maltego**, **MISP Project**, and other OSINT tools  
- **Industry vertical sharing groups** (e.g., Brazilian banks sharing threat data)

---

### 🔄 Threat Intelligence Sharing Standards

#### **STIX (Structured Threat Information eXpression)**
- A structured language for representing cyber threat information.  
- Describes **actors**, **incidents**, **indicators of compromise (IoCs)**, **tactics**, and **recommended mitigations**.  
- Designed for **collaboration** and **machine-readable exchange**.

#### **TAXII (Trusted Automated eXchange of Indicator Information)**
- A **protocol** for exchanging cyber threat intelligence (CTI) over HTTPS.  
- Defines RESTful APIs for sharing CTI between clients and servers.  
- Enables **standardized**, automated sharing without custom integrations.

> 💡 Example: An organization (TAXII client) requests or publishes new threat intelligence to a TAXII server, which shares it with other subscribers.

---

### ⚙️ The Threat Intelligence Lifecycle

To transform **raw data** into **usable intelligence**, follow these six stages:

1. **Identify Primary Threats**  
   - Focus on the threats most critical to your network.  
   - Use sources like **CVSS** and **FortiGuard** to determine high-severity or industry-specific risks.  
   - Example:  
     - Hospitals → focus on **ransomware**  
     - Defense agencies → focus on **data exfiltration**

2. **Collect Threat Information**  
   - Gather data from internal and external sources.

3. **Process the Information**  
   - Filter out irrelevant data (“separate the noise from the signal”).  
   - Establish **baselines of normal network behavior**.

4. **Analyze the Data**  
   - Identify **Indicators of Compromise (IoCs)** and link them to threat actor tactics and campaigns.

5. **Disseminate Findings**  
   - Share intelligence with **partners**, **allies**, or **industry peers** using standards like **STIX** and **TAXII**.

6. **Implement Lessons Learned**  
   - Update your threat models, detection methods, and priorities based on new insights.

---

### ✅ Summary

Threat intelligence transforms **raw cybersecurity data** into **actionable knowledge** that helps organizations:

- Detect and prevent attacks  
- Prioritize vulnerabilities  
- Share critical insights with the security community  

> 🧩 Effective threat intelligence is **relevant**, **actionable**, and **contextual** — driving smarter, faster, and more adaptive security decisions.
