# 📶 Wi-Fi

## 💬 Overview

**Wi-Fi**, based on the **IEEE 802.11 standards**, is a **wireless technology** used for **local area networking (LAN)** of devices.  
It operates similarly to **Ethernet** by using **IP at the network layer** and **TCP/UDP at the transport layer**, but unlike wired networks, **Wi-Fi transmits data through radio waves or microwaves** instead of physical cables.

---

## 🌐 How Wi-Fi Works

Wi-Fi networks often involve components such as:

- 📡 **Routers and Access Points (APs)**  
- 🔁 **Switches**  
- 🌍 **Domain Name System (DNS)**  

In most cases, **wireless networks connect to wired networks** through a **gateway router**.

🏠 **Example:**  
Your home Wi-Fi network lets your devices communicate wirelessly.  
However, for internet access, your **home router** acts as a **gateway**, linking your internal Wi-Fi to the **wide area network (WAN)** via wired technologies like **DSL**, **cable internet**, or **fiber**.

---

## ⚖️ Wired vs. Wireless Networks

| Feature | Wired Network | Wireless (Wi-Fi) Network |
|----------|----------------|---------------------------|
| 🔌 **Transmission Medium** | Twisted copper wires or fiber optics | Radio waves or microwaves |
| 🚶‍♂️ **Mobility** | Limited – devices are tethered by cable | High – users can move freely within Wi-Fi range |
| 🔒 **Security Risk** | Lower (physical access required) | Higher (data can be intercepted wirelessly) |

---

## 📡 Advantages of Wi-Fi

- 📱 **Mobility:** Move freely within the coverage area  
- 🔄 **Ease of Setup:** No need for cables  
- 🧑‍🤝‍🧑 **Connectivity:** Multiple devices can connect simultaneously  

---

## ⚠️ Disadvantages of Wi-Fi

- 🔓 **Security Risks:** Susceptible to eavesdropping and unauthorized access  
- 📉 **Signal Interference:** Affected by walls, microwaves, and other devices  
- 🐢 **Speed Limitations:** Generally slower than wired Ethernet  

---

## 🛡️ Wi-Fi Security Evolution

Because data travels through the air, Wi-Fi requires **strong encryption and authentication** to remain secure.

### 🔐 1. WEP (Wired Equivalent Privacy)
- The first Wi-Fi security standard.
- Provided basic encryption but was **easily cracked** and is now **deprecated**.

### 🔐 2. WPA (Wi-Fi Protected Access)
- Introduced to improve WEP’s weaknesses.
- Added stronger encryption and key management.

### 🔐 3. WPA2
- Based on **AES (Advanced Encryption Standard)**, developed by **NIST (National Institute of Standards and Technology)**.
- Introduced **enterprise-grade authentication (802.1X)** for organizations.
- Home users relied on **pre-shared keys (PSK)**.

### 🔐 4. WPA3 (Released in 2018)
- Uses a **new, secure handshake** process.
- Simplifies device onboarding and increases key sizes.
- Offers **stronger encryption** and **better protection** against brute-force attacks.

---

## 🧱 Enterprise vs. Home Security

| Security Level | Authentication Method | Encryption | Notes |
|----------------|-----------------------|-------------|-------|
| 🏠 **Home** | Shared passphrase (PSK) | AES (WPA2/WPA3) | Easier setup, but weak passwords reduce security |
| 🏢 **Enterprise** | 802.1X Authentication | AES or WPA3-Enterprise | Uses RADIUS and certificates for strong user verification |

⚠️ **Tip:** Even with strong encryption, weak passwords can make your Wi-Fi vulnerable.

---

## ☠️ Threats and Attacks on Wi-Fi

### 🧠 **Social Engineering**
Bad actors exploit human carelessness through tricks such as fake Wi-Fi networks.

### 🎯 **Evil Twin Attacks**
Hackers set up **rogue access points (APs)** that imitate legitimate networks.  
When users connect, attackers perform **man-in-the-middle (MITM)** attacks to steal:

- 🔑 Account credentials  
- 💳 Credit card information  
- 📁 Sensitive data  

> 📱 Your device may automatically reconnect to known SSIDs, allowing attackers to exploit remembered networks.

---

## 🧰 Wi-Fi Security Best Practices

✅ **Do’s:**
- 🔒 Use the latest encryption protocol (preferably **WPA3**)  
- 🧱 Change default **SSID** and **password** on your router/AP  
- 🔑 Choose **complex, unique passphrases**  
- ⚙️ Keep router **firmware up to date**  
- 👀 Monitor devices connected to your network  
- 🚫 Disable WPS (Wi-Fi Protected Setup) if not needed  
- 🌐 Use a **VPN** when using public Wi-Fi  
- 🔍 Enable **network monitoring** or intrusion detection  

🚫 **Don’ts:**
- Don’t connect to **open** or **unknown SSIDs**  
- Don’t reuse passwords between networks  
- Don’t ignore firmware updates  

---

## 🧩 Advanced Wi-Fi Security Features

Modern **access points (APs)** and routers include:

- 🧠 **Traffic inspection** and **malware detection**
- ⚔️ **Rogue AP detection and suppression** (⚠️ legality varies by region)
- 🧩 **Network segmentation** (separate guest and internal networks)
- 🔑 **Access Control Lists (ACLs)** to allow only trusted devices
- 📊 **Real-time monitoring** and alerting for anomalies

---

## 🏗️ Fortinet Secure Wi-Fi Solutions

Fortinet provides a **Secure Wireless LAN Solution** with integrated protection and management through its security fabric.

| Product | Description |
|----------|--------------|
| **FortiAP™** | Secure wireless access points |
| **FortiSwitch™** | Intelligent network switching |
| **FortiWiFi®** | Wireless connectivity with embedded security |
| **FortiGate®** | Next-generation firewall for unified threat management |

---

## 🧠 Summary

| Key Point | Description |
|------------|--------------|
| **Definition** | Wireless LAN technology based on IEEE 802.11 standards |
| **Transmission Medium** | Radio or microwaves instead of cables |
| **Main Advantage** | Mobility and convenience |
| **Main Disadvantage** | Security vulnerabilities |
| **Security Protocols** | WEP → WPA → WPA2 → WPA3 |
| **Best Practices** | Use WPA3, strong passwords, updated firmware, and VPN for public Wi-Fi |

✅ **In summary:**  
Wi-Fi provides **freedom and connectivity**, but it must be **secured through strong encryption, authentication, and safe user behavior** to protect against modern cyber threats. 🌍🔐📡
