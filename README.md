# 💻 Android Hacking Tools

A well-organized collection of essential tools for Android developers, modders, and reverse engineers who work on APK modifications, game cheats, and Android mod menus.

> ⚠️ **For Educational Purposes Only**

---

## 📁 Contents

- [APK Tools](#-apk-folder-apks)
- [ZIP Tools](#️-zip-folder-zip-tools)
- [Templates](#-templates)
- [Frida Scripts](#-frida-scripts) *(new)*
- [Contributing](#-contributing)
- [Support](#️-support--donations)

---

## 📂 APK Folder (APKs)

Pre-installed APK-based tools for on-device Android modification and development:

| Tool | Description |
|------|-------------|
| **AIDE** | Android IDE for coding and app development on the go |
| **AntiSplit-G2 v1.3** | Tool for merging split APKs |
| **APK Tool M** | Versatile APK decompiler and builder |
| **il2cppDumperGUI** | GUI version of IL2CPP Dumper for Unity games |
| **Meow Transparent** | Tool with floating UI features (modding overlay) |
| **MT Manager** | Powerful file manager with APK editing tools |
| **NP Manager** | Patching and modding utility for Android apps |

---

## 🗜️ ZIP Folder (ZIP Tools)

PC-based portable tools packed in ZIP format:

| Tool | Description |
|------|-------------|
| **APK Easy Tool v1.60 (Portable)** | GUI-based APK decompiler/recompiler |
| **HxD Portable** | Lightweight and powerful hex editor |

---

## 🧩 Templates

Inside the `MOD MENU` folder, you'll find:

- **Android Mod Menu Template** – Clean and modular template originally inspired by the **LGL Team**.  
  Perfect for creating your own custom in-game mod menus with toggleable cheats and UI elements.

---

## 🪝 Frida Scripts

A curated collection of Frida dynamic instrumentation scripts for Android reverse engineering and security research.

> 📌 Scripts are organized by category inside the `frida-scripts/` folder.

| Category | Description |
|----------|-------------|
| `ssl-pinning/` | Bypass SSL/TLS certificate pinning (OkHttp3, TrustManager, etc.) |
| `root-detection/` | Bypass common root detection checks (RootBeer, su binary, etc.) |
| `memory/` | Memory scanning and runtime value manipulation |
| `il2cpp/` | IL2CPP metadata dumping and Unity game hooks |

**Basic usage:**
```bash
frida -U -f com.target.app -l frida-scripts/ssl-pinning/bypass-okhttp3.js
```

> Community contributions welcome — see [Contributing](#-contributing) below.

---

## 🤝 Contributing

Contributions are open! If you have tools, scripts, or templates that belong here:

1. **Fork** this repository
2. Add your files to the appropriate folder
3. Open a **Pull Request** with a short description

Read the full guidelines in [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

## ❤️ Support & Donations

If you'd like to support this project, you can send your donation via **GCash**:

**📱 GCash Number:** `0962 797 2598`  
**Recipient Name:** *Jcrist Vincent Orhen*

Your support means a lot and helps keep the project alive!

---

## ⭐ Star This Repository

If you find this toolkit helpful, don't forget to [🌟 star the repo on GitHub](https://github.com/jcrvnx/android-hacking-tools) to show your support!

---

## 📈 Repository Stats

![GitHub Stars](https://img.shields.io/github/stars/jcrvnx/android-hacking-tools?style=social)
![GitHub Forks](https://img.shields.io/github/forks/jcrvnx/android-hacking-tools?style=social)

### 🔥 Stars Over Time

[![Stargazers over time](https://starchart.cc/jcrvnx/android-hacking-tools.svg)](https://starchart.cc/jcrvnx/android-hacking-tools)

---

## 🛠️ Made with passion by

[**Jcrist Orhen**](https://facebook.com/jcristorhen)  
Founder of Nyxar Technologies – Empowering Android Reverse Engineering and Modding Communities
