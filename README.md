# VPN-Setup-and-Privacy-Test-
Understand the role of VPNs in protecting privacy and secure communication.  

---

## 🔑 Steps Performed :
1. **Chose VPN Service** – Registered with `ProtonVPN` (free account).  
2. **Downloaded & Installed Client** – Installed `ProtonVPN` desktop client.  
3. **Connected to VPN Server** – Chose the closest server for stable speed.  
4. **Verified IP Address** – Used [whatismyipaddress.com](https://whatismyipaddress.com) to confirm IP changed.  
5. **Tested Encrypted Traffic** – Browsed websites via VPN to ensure traffic was tunneled securely.  

---

## Screenshots:
* **Showing IP From `whatismyipaddress.com` Before Connecting to the VPN.**
  <img width="1426" height="625" alt="ip" src="https://github.com/user-attachments/assets/679a901f-dbec-4d2a-9b47-5451f127b069" />

* **Showing Broesing Speed Before Connecting to VPN**
  <img width="1178" height="671" alt="speed test" src="https://github.com/user-attachments/assets/33e940d9-2b89-4ab5-8dc0-27910483ed38" />

* **Showing IP From `whatismyipaddress.com` After Connecting to the VPN.**
 <img width="1507" height="651" alt="ip aft VPN" src="https://github.com/user-attachments/assets/0a03f0bb-54c2-490e-bc37-0eef651bb620" />


* **Showing Broesing Speed After Connecting to VPN**
  <img width="1172" height="688" alt="speed test with VPN" src="https://github.com/user-attachments/assets/e3eb19bb-10a6-46db-9910-87fd3667ee2b" />
  
---
  ## Findings:

  - **Performance**: Browsing speed was slightly reduced compared to direct connection (expected due to encryption and routing through VPN servers).

---

## Tools Used:

- **For VPN:** [Windscribe](https://windscribe.com/) `Free`, [Proton VPN](https://protonvpn.com/) `Free`
- **For IP Check:** [What is My IP Address](https://whatismyipaddress.com/) `Free`
- **For Speed Test:** [Speed Test](https://www.speedtest.net/) `Free`

---

## Research VPN Encryption & Privacy

- **Encryption Standards:** Most reputable VPNs (like ProtonVPN and Windscribe) use AES-256 encryption, which is considered military-grade and virtually unbreakable by brute force. Some also support ChaCha20 (used with WireGuard protocol) for faster performance.

- **Tunneling Protocols:** VPNs rely on secure tunneling protocols such as OpenVPN, IKEv2/IPSec, and WireGuard to create an encrypted channel between the device and the VPN server. These ensure data confidentiality and integrity.

- **IP & Location Masking:** A VPN hides your real IP address and replaces it with the VPN server’s IP, making online activity harder to trace back to you and protecting against website tracking or ISP monitoring.

- **Privacy Features:**

  * Prevents ISP and public Wi-Fi providers from seeing browsing activity.

  * Protects sensitive data (e.g., logins, banking info) from interception.

  * Some VPNs include a no-logs policy, ensuring that even the provider does not track user activity.

- **Limitations:** While VPNs improve privacy, they are not a full anonymity tool — the VPN provider can still technically see your traffic unless they enforce strict no-log policies. For complete anonymity, tools like Tor may be needed in combination with a VPN.

## Summary:

VPNs provide an extra layer of privacy and security by encrypting internet traffic and masking real IP addresses. They are especially useful when using public Wi-Fi or bypassing geo-restrictions. However, free VPNs may come with limitations in speed, server availability, and potential trust issues with providers.  
