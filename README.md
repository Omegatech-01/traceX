# traceX
# 🕵️‍♂️ traceX

![traceX Banner](https://i.imgur.com/3hK0j9v.png)  
![traceX Hacker Banner](https://i.imgur.com/YOUR_SECOND_BANNER.png)  

**traceX** is a **Termux-based hacker tool** for network scanning, camera detection, IP lookup, and more. It comes with **matrix-style terminal animations**, hacker logs, and a fully interactive menu.  

---

## 🚀 Features
- 🌐 Show public IP & location  
- 🖧 Scan LAN for devices  
- 📷 Detect cameras on your network  
- 🔓 Fetch open cameras from Insecam.org  
- 🖼 Grab live snapshots from LAN cameras  
- 🛡 Brute-force camera login (for testing your own devices)  
- ☁️ 3-day weather forecast  
- 💻 System information display  
- 🎨 Hacker-style matrix animation and logs  

---

## ⚡ Installation & Usage

<!-- Copy Command Button -->
<button onclick="navigator.clipboard.writeText(`git clone https://github.com/Omegatech-01/traceX.git
cd traceX
chmod +x traceX
mv traceX /data/data/com.termux/files/usr/bin/
pkg install nmap curl jq figlet lolcat medusa
termux-setup-storage
./traceX`)">📋 Copy All Commands</button>

<details>
<summary>Or view commands manually</summary>

```bash
# Clone the repository
git clone https://github.com/Omegatech-01/traceX.git
cd traceX

# Make it executable
chmod +x traceX

# (Optional) Move to PATH for global access
mv traceX /data/data/com.termux/files/usr/bin/

# Install required dependencies
pkg install nmap curl jq figlet lolcat medusa

# Grant storage access in Termux if needed
termux-setup-storage

# Run traceX
./traceX   # or just 'traceX' if in PATH
.




---

🖥 Hacker Logs & Terminal Visuals

Sample Hacker Banner on Launch:

╔════════════════════════════╗
║        OMEGA TRACE         ║
╚════════════════════════════╝
Welcome Omega, Ready To Trace Bitched!

      ▄▄▄▄▄▄▄
    ▄▀░░░░░░░▀▄
   █░░█░░░░░█░░█
  █░░░▀▀▀▀▀▀░░░█
  █░░░░░░░░░░░░█
  █░░░▀▄░░░▄▀░░░█
   █░░░░▀▀▀░░░░█
    ▀▄░░░░░░░▄▀
      ▀▀▄▄▄▄▀▀

Matrix rain animation preview:

01010110101101001010101101001010
00101011010110101010100101010101
11001010100101011010101001010101
... (more random binary)

Sample command menu inside traceX:

1) Show My Public IP & Location
2) Scan LAN for Devices
3) LAN Camera Detection
4) Fetch Open Cameras (Insecam)
5) Grab Live Screenshots
6) Brute-force Camera Login
7) Weather Forecast
8) System Info
9) Exit

LAN camera scan log preview:

[*] Scanning 192.168.1.0/24 for open cameras...
[+] Camera found: 192.168.1.101
[+] Camera found: 192.168.1.105
[+] Camera found: 192.168.1.110
Camera IP list saved to /tmp/camera_ips.txt

Snapshot grab log preview:

[*] Attempting snapshot grab from detected cameras...
[+] Snapshot saved for 192.168.1.101 -> /sdcard/192.168.1.101_snapshot.jpg
[+] Snapshot saved for 192.168.1.105 -> /sdcard/192.168.1.105_snapshot.jpg


---

📝 Credits

Made with ❤️ by Omega Dixon (Omegatech-01)

Terminal visuals powered by figlet and lolcat

Network tools powered by nmap, curl, jq, medusa



---

> Disclaimer: For educational and testing purposes only. Do not use on networks or devices you do not own.
