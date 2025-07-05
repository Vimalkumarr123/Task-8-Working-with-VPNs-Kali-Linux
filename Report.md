# 📊 VPN Summary Report (Kali Linux)

## 🧠 Benefits of VPNs
- Encrypts all outgoing and incoming traffic
- Hides user’s actual IP address
- Secures data on public Wi-Fi
- Bypasses content and geo-restrictions
- Prevents ISP tracking

## ⚠️ Limitations of VPNs
- Can reduce network speed
- VPN provider may log data (trust is essential)
- Cannot prevent all browser-based tracking (e.g., cookies, fingerprinting)
- Free VPNs often have limited servers and bandwidth

## 🔧 Kali Linux Setup Summary
- Installed ProtonVPN CLI using `pipx install protonvpn-cli`
- Connected to VPN with `protonvpn-cli connect --fastest`
- Verified IP address change using `curl ifconfig.me`
- Used CLI commands to check status and disconnect
- Noticed slight drop in browsing speed during VPN connection

## 💡 Outcome
Hands-on understanding of VPN architecture, encryption mechanisms, and privacy protection on Kali Linux.
