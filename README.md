# 🔐 CYBER-SECURITY-8

## Task 8: Understand and Use a VPN for Privacy and Secure Communication

### 📌 Objective

The objective of this task is to understand how a **Virtual Private Network (VPN)** helps protect online privacy and secure communication.

In this task, a reputable free VPN service is installed and configured. A VPN connection is established, the public IP address is checked before and after connecting, and the differences in browsing and network behavior are observed.

---

## 🛠️ Tools Used

* 💻 Windows PC
* 🌐 Microsoft Edge / Web Browser
* 🔐 Free VPN Client
* 🛡️ Proton VPN Free Tier / Windscribe Free
* 🌍 IP Address Checking Website

---

## 🔎 Task Performed

The following steps were completed as part of the VPN setup and testing:

1. Selected a reputable free VPN service.
2. Downloaded and installed the VPN client.
3. Logged into the VPN application.
4. Connected to an available VPN server.
5. Checked the public IP address before connecting.
6. Checked the public IP address after connecting.
7. Verified that the public IP address changed.
8. Browsed a website while connected to the VPN.
9. Disconnected the VPN and compared the connection.
10. Researched VPN encryption, privacy features, benefits, and limitations.

---

## 🌐 IP Address Verification

The public IP address was checked before and after connecting to the VPN.

| Test             | VPN Status     | IP Address         | Result             |
| ---------------- | -------------- | ------------------ | ------------------ |
| Before VPN       | ❌ Disconnected | Original IP        | Normal connection  |
| After VPN        | ✅ Connected    | VPN IP             | IP address changed |
| After Disconnect | ❌ Disconnected | Original/normal IP | VPN disconnected   |

> **Privacy Note:** Do not publish your real IP address in a public GitHub repository. If a screenshot contains your IP address, blur or redact it before uploading.

---

## 🔐 How a VPN Protects Privacy

A VPN creates an encrypted connection between the user's device and the VPN server.

Instead of directly connecting to websites through the normal network path, the user's traffic is routed through the VPN server.

### Basic Flow

```text
Without VPN:

Your Device → Internet Service Provider → Website


With VPN:

Your Device → Encrypted VPN Connection → VPN Server → Website
```

A VPN can help protect traffic from local network observers, especially when using untrusted networks such as public Wi-Fi.

---

## 🛡️ VPN Encryption and Privacy

VPN services use encryption protocols to protect network traffic between the device and VPN server.

A VPN can help:

* 🔒 Encrypt network traffic between the device and VPN server.
* 🌐 Hide the user's public IP address from websites.
* 📶 Improve privacy on untrusted networks.
* 🛡️ Reduce exposure to local network monitoring.

However, a VPN does **not** provide complete anonymity or protect against every online threat.

---

## ⚖️ VPN Benefits

### ✅ Privacy

A VPN can hide the user's public IP address from websites and route traffic through a VPN server.

### ✅ Secure Public Wi-Fi

VPN encryption can provide additional protection when using untrusted networks.

### ✅ Encrypted Connection

Traffic between the device and VPN server is protected by the VPN's encryption and tunneling protocols.

### ✅ IP Address Protection

Websites generally see the VPN server's public IP address instead of the user's normal public IP address.

---

## ⚠️ VPN Limitations

A VPN is not a complete cybersecurity solution.

* A VPN does not automatically protect against phishing.
* A VPN does not guarantee complete anonymity.
* A VPN provider may still have visibility into some connection information.
* VPNs cannot prevent malware if the user downloads and executes malicious software.
* Connection speed may decrease depending on the VPN server and network conditions.
* Free VPN services may have limitations such as server availability, speed, or data limits.

---

## 📊 VPN Connection Comparison

| Feature                 | Without VPN       | With VPN               |
| ----------------------- | ----------------- | ---------------------- |
| Public IP               | Normal IP         | VPN server IP          |
| VPN Tunnel              | ❌ No              | ✅ Yes                  |
| Traffic to VPN Server   | Normal connection | 🔐 Encrypted           |
| Privacy on Public Wi-Fi | Lower             | Improved               |
| Connection Speed        | Usually normal    | May be slightly slower |

---

## 📸 Evidence

A screenshot showing the VPN client connected to a VPN server should be included as evidence.

Recommended file:

```text id="q8k4mp"
Screenshots/
└── vpn-connected.png
```

If an IP-check screenshot is available, it can also be included:

```text
Screenshots/
├── vpn-connected.png
└── ip-address-check.png
```

> Before uploading screenshots to GitHub, hide your real IP address and any personal account information.

---

## 📁 Project Structure

```
CYBER-SECURITY-8/
│
├── README.md
│
├── Report/
│   └── vpn-setup-and-analysis-report.md
│
└── Screenshots/
    └── vpn-connected.png
```

---

## 🎯 Learning Outcomes

After completing this task, I learned:

* What a VPN is and how it works.
* How to install and connect to a VPN.
* How VPNs can improve privacy on untrusted networks.
* How a VPN can change the visible public IP address.
* The basic role of VPN encryption.
* The benefits and limitations of free VPN services.
* Why a VPN should be considered one part of a broader security strategy.

---

## ✅ Conclusion

This task provided hands-on experience with VPN configuration and privacy protection.

The VPN connection successfully demonstrated how routing traffic through a VPN server can change the visible public IP address and provide an encrypted connection between the device and the VPN server.

A VPN can be a useful privacy and security tool, but it should be combined with other security practices such as strong passwords, Multi-Factor Authentication, secure browsing habits, and updated software.

---

## ⚠️ Disclaimer

This project is intended for **educational and cybersecurity awareness purposes only**.

The VPN was used for legitimate privacy and security testing on an authorized device and network. No unauthorized access or malicious activity was performed.
