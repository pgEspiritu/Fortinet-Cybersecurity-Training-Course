## 🧠 Insider Threat

When addressing cybersecurity, organizations often focus on **external threats**. However, a significant number of security breaches are caused by **insiders** — individuals with legitimate access who, intentionally or unintentionally, compromise security.  
Cybersecurity teams must therefore include **insider threat management** in their defensive strategy through employee awareness, monitoring, and culture-building.

---

### 🔍 What is an Insider Threat?

An **insider threat** is any person with **authorized access** to an organization’s systems, networks, or data who poses a **physical or cyber risk**.  
This includes:
- Current or former employees  
- Contractors and business partners  
- Board members  
- Imposters posing as legitimate insiders  

---

### ⚖️ Categories of Insider Threats

Insider threats are broadly divided into two main groups:

#### 🧩 1. Negligent (Unintentional) Insiders
Individuals who **unintentionally** assist bad actors due to **human error**, **poor judgment**, or **carelessness**.

#### 🦠 2. Malicious (Intentional) Insiders
Individuals who **deliberately** cause harm to the organization for **personal gain**, **revenge**, or **outside influence**.

---

### 💀 Malicious Insider Subtypes

| Type | Description | Example |
|------|--------------|----------|
| 🐺 **Lone Wolf** | Acts independently with malicious intent, often for revenge or ideology. | Disgruntled employee deleting data. |
| 🤝 **Collaborator** | Works with an external party (competitor, criminal group, or nation-state). | Insider sharing data with a foreign entity. |
| 🕵️ **Mole** | An outsider who gains internal access by impersonation. | *Emily Williams* case from Social Engineering Part B. |

**Goals:** Espionage, fraud, IP theft, and sabotage.  
> Example: In 2020, a former executive stole trade secrets from a self-driving car company and was sentenced to 18 months in prison.

---

### 😬 Careless Insider Subtypes

| Type | Description | Example |
|------|--------------|----------|
| 🎯 **Pawn** | Manipulated into assisting a bad actor, usually via social engineering. | Head of InfoSec duped by a malicious birthday card. |
| 🙈 **Goof** | Disregards security policies out of arrogance or ignorance. | Employee disabling antivirus or sharing passwords. |

---

### 🧰 Attack Vectors & Methods

#### 🏢 Physical Vectors
- **Tailgating / Piggybacking** – Gaining physical access by following someone with authorization.  
- **Shoulder Surfing** – Observing credentials or data visually.  
- **Dumpster Diving** – Retrieving discarded sensitive materials.  
- **Physical Eavesdropping** – Listening to private conversations.

#### 🌐 Digital Vectors
- **Network Eavesdropping / Sniffing** – Capturing data over insecure networks (especially wireless).  
- **Phishing, Spear Phishing, Whaling** – Targeting employees via deceptive emails.  
- **Smishing / Vishing / Pretexting** – Social engineering via SMS, voice calls, or fabricated stories.  
- **Watering Hole Attacks** – Luring targets via trusted but compromised websites or social media.

---

### 🧭 Detecting Insider Threats

#### ⚠️ Behavioral Indicators
- Sudden dissatisfaction, hostility, or disengagement.  
- Overly enthusiastic assumption of extra privileges.  
- Attempts to **bypass policies** or **routinely violate rules**.  
- Personality or attitude changes without clear reason.

#### 💻 Digital Indicators
- Unusual logins (e.g., off-hours, 4 AM sessions).  
- Accessing or transferring atypical data volumes.  
- Requests for system access unrelated to role.  
- Use of unauthorized USB drives or personal devices.  
- Network crawling or data exfiltration activities.

---

### 🛡️ Defensive Strategies

#### 🔒 Personal Best Practices
- Follow all security protocols — no shortcuts.  
- Lock workstations; never expose credentials.  
- Disallow tailgating — always verify.  
- Encrypt and secure sensitive files.  
- Keep endpoint protections enabled.  
- Avoid sharing proprietary data externally.  
- Patch systems promptly when updates are released.

#### 🧩 Organizational Measures
1. **Identify and Prioritize Critical Assets**  
   Rank systems, data, and facilities to secure high-value targets first.  

2. **Leverage Analytics and Machine Learning**  
   - Use **UEBA (User and Entity Behavior Analytics)** to detect anomalies.  
   - Apply **database activity monitoring** to flag unauthorized access.  

3. **Deploy Deception Tools**  
   - Use **honeypots** and **deception software** (e.g., *FortiDeceptor*) to detect insider reconnaissance.  
   - Correlate findings with threat intelligence to improve response.  

4. **Policy & Training**  
   - Define, document, and disseminate clear security policies.  
   - Conduct regular **training and comprehension tests**.  
   - Reinforce accountability and policy compliance.  

5. **Culture of Security Awareness**  
   - Promote shared responsibility for cybersecurity.  
   - Encourage employees to report suspicious behavior.  
   - Reward adherence to security practices.  

---

### 🧩 Mermaid Diagram — Insider Threat Landscape

```mermaid
flowchart TD
  A[Insider Threats] --> B[Negligent Insiders]
  A --> C[Malicious Insiders]

  B --> D[Pawn<br/>(manipulated via phishing, tailgating)]
  B --> E[Goof<br/>(ignores policies, careless)]

  C --> F[Lone Wolf<br/>(acts alone)]
  C --> G[Collaborator<br/>(works with external group)]
  C --> H[Mole<br/>(imposter gaining internal access)]

  A --> I[Indicators & Defenses]
  I --> J[Behavioral & Digital Monitoring]
  I --> K[Policies & Training]
  I --> L[Culture of Security Awareness]

  classDef category fill:#f6c,stroke:#a03,stroke-width:1px;
  classDef defense fill:#cfc,stroke:#080,stroke-width:1px;
  class B,C,D,E,F,G,H category;
  class I,J,K,L defense;
```

---

### ✅ Key Takeaways

- Insider threats are as dangerous as external ones and often harder to detect.
- They include both malicious actors and careless employees.
- Continuous monitoring, policy enforcement, and a security-aware culture are critical.
- Remember: Security starts from within.
