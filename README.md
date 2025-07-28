# O-SAMEER - Wi-Fi Jamming Tool

`O-SAMEER` (Offensive Security Attack Method for Ethical Exploits and Research) is a powerful Wi-Fi jamming tool built for ethical hacking, security testing, and research purposes only. It uses `aircrack-ng` suite under the hood to discover and deauthenticate nearby wireless networks in monitor mode.

---

## 👨‍\U0001F4BB Author

**Syed Sameer Ul Hassan**
📧 Email: [syedsameerulhassan@Yahoo.com](mailto:syedsameerulhassan@Yahoo.com)
🔗 GitHub: [gith](https://github.com/syed-sameer-ul-hassan)[ub.com/syed-sameer-ul-hass](https://sameer-shah-CS.netlify.app)[an](https://github.com/syed-sameer-ul-hassan)

---

## ⚠️ Disc[laimer & Legal Warning](https://github.com/syed-sameer-ul-hassan)

> **[This to](https://github.com/syed-sameer-ul-hassan)\*\*\*\*\*\*\*\*\*\*\*\*ol is for educational purposes only!**
> Do NOT use it on any network you do not own or have explicit permission to test.
> Unauthorized use of this tool against any third-party network is illegal and strictly prohibited.
> The developer will not be responsible for any misuse or damage caused by this software.

---

## 📦 Installation

Make sure you're on **Kali Linux** or a Debian-based system with root/sudo privileges.

### ✅ Option A: Install via `.deb` Package

Download from the [Releases](https://github.com/syed-sameer-ul-hassan/o-sameer/releases):

```bash
sudo dpkg -i deb/o-sameer_1.0.0_amd64.deb
```

Then run it:

```bash
sudo o-sameer
```

---

### ✅ Option B: Manual System-wide Installation

```bash
sudo apt update
sudo apt install aircrack-ng git -y

git clone https://github.com/syed-sameer-ul-hassan/o-sameer.git
cd o-sameer
chmod +x o-sameer

# Install to /usr/local/bin so it's globally accessible
sudo install o-sameer /usr/local/bin/
```

Now you can run the tool from anywhere:

```bash
sudo o-sameer
```
