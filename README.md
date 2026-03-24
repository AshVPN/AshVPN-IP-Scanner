# 🚀 AshVPN IP Scanner | Professional Edition

![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/License-Freeware-brightgreen.svg)

The **AshVPN IP Scanner** is a high-performance, asynchronous Windows tool built specifically for network engineers, bypass enthusiasts, and VPN creators. 

Tired of dead V2Ray nodes? Need to find open DNS resolvers for DNSTT tunneling? Standard scanners will crash your RAM or take hours. The AshVPN engine utilizes a highly optimized Python generator and 400 concurrent asynchronous threads to blast through massive subnets (like Cloudflare's /13) **instantly and without crashing.**

### 🔥 Why This is the Ultimate Scanner:
* **⚡ Blazing Fast Asynchronous Core:** Scans up to 400 IPs simultaneously. Drops dead connections instantly to save time.
* **🧠 Zero RAM Spikes:** Built with a dynamic memory engine. You can queue up millions of IPs and your RAM usage will stay flat.
* **🎯 Raw UDP DNS Testing (DNSTT):** Doesn't just ping. It sends raw A-Record DNS payloads over UDP to definitively prove if an IP is an open resolver.
* **🛡️ Premium Bypass Networks:** Built-in CIDR ranges for networks with excellent Middle East routing (Gcore, Akamai, OVH, Oracle, Scaleway, Edgio).
* **📋 1-Click V2Ray Export:** Filters your results and instantly copies them to your clipboard in a comma-separated or newline format, ready for your configs.

---

### ⚙️ How to Use (Step-by-Step)

It is incredibly simple to use. No installation required!

1. **Download:** Go to the [Releases page](../../releases) and download `AshVPN_IP_Scanner_v1.exe`.
2. **Run:** Double click the `.exe` (If Windows SmartScreen blocks it, click "More Info" -> "Run Anyway").
3. **Select Targets:** * Toggle the built-in providers (Cloudflare, Fastly, Gcore, etc.).
   * OR check the "Clean DNS List" for DNSTT hunting.
   * OR paste your own custom CIDR ranges (e.g., `104.16.0.0/24`).
4. **Scan:** Hit the green **START** button. 
5. **Export:** Go to the **Live Results** tab. Select your filter (e.g., "DNSTT Ready"), and click **Copy All Working Ones**.

---

### 👨‍💻 Developed By
**Ash** * ✈️ **Telegram Bot:** [@WhiteIPCheck_Bot](https://t.me/WHITEIPCHECK_Bot)
* 🌐 **GitHub:** [AshVPN](https://github.com/AshVPN)

*Note: This tool is provided for educational and network diagnostics purposes.*
