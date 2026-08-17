# Organisation Network Security - Cisco Packet Tracer Lab

## 📌 Project Overview
This project is focused on securing an enterprise network infrastructure for **TechNova Solutions** against unauthorized Wi-Fi access attempts. It involves configuring static WAN IPs, securing wireless SSIDs using WPA2-AES, implementing MAC address filtering, and updating administrative router credentials.

---

## 🛠️ Objectives & Configurations Implemented

1. **Part 1: WAN Configurations**
   * Configured static IP address parameters on the wireless router via the admin PC interface.
   * **IP Address:** `10.0.0.2`
   * **Subnet Mask:** `255.0.0.0`
   * **Default Gateway:** `10.0.0.1`
   * **DNS Server:** `195.0.0.1`

2. **Part 2: Securing the Wi-Fi Network**
   * **Wireless Band:** `2.4 GHz`
   * **SSID:** `IT_Dept`
   * **Security Type:** `WPA2-Personal`
   * **Encryption Method:** `AES`
   * **Passphrase:** `cisco123`

3. **Part 3: MAC Address Filtering**
   * Enabled MAC filtering to restrict network access strictly to authorized employee laptops.
   * Set mode to **Permit PCs listed below**, blocking unauthorized intruder devices.

4. **Part 4: Administrative Security**
   * Strengthened router access by replacing default credentials with a secure custom admin password (`cisconet123`).

5. **Part 5: Verification & Testing**
   * Tested connectivity from employee PCs to the company web server (`www.cisco.com`).
   * Verified that unauthorized devices (Intruder Laptop) are successfully blocked from connecting to the `IT_Dept` SSID.

---

## ⚙️ Tools Used
* **Cisco Packet Tracer** (Network Simulation & Topology Design)

## 👨‍💻 Author
* **Harsh**
<img width="954" height="674" alt="image" src="https://github.com/user-attachments/assets/18dea623-f334-4d35-973e-90e3436c8ccf" />
