# 🤝 Contributing to Android Hacking Tools

Thanks for your interest in contributing! This repo is a community-driven collection of tools, scripts, and templates for Android reverse engineering, APK modding, and game hacking — for educational purposes only.

---

## 📋 What You Can Contribute

- **Frida Scripts** — SSL pinning bypass, root detection bypass, memory scanning, il2cpp hooks
- **APK Tools** — Useful Android tools not yet in the collection
- **Mod Menu Templates** — Cleaner or more modular templates
- **ZIP Tools** — Portable PC-side tools for modding workflows
- **Documentation** — Fixes, clarifications, better descriptions

---

## 🚀 How to Contribute

### 1. Fork the Repository

Click the **Fork** button at the top right of this repo.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/android-hacking-tools.git
cd android-hacking-tools
```

### 3. Create a Branch

```bash
git checkout -b feat/your-contribution-name
```

### 4. Add Your Files

Place your files in the appropriate folder:

```
android-hacking-tools/
├── APKS/               → APK tools (on-device)
├── ZIP/                → Portable PC tools
├── TEMPLATES/          → Mod menu templates
└── frida-scripts/      → Frida scripts (new section)
    ├── ssl-pinning/
    ├── root-detection/
    ├── memory/
    └── il2cpp/
```

### 5. Commit and Push

```bash
git add .
git commit -m "feat: add [brief description]"
git push origin feat/your-contribution-name
```

### 6. Open a Pull Request

Go to the original repo and click **New Pull Request**. Describe what you added and why it's useful.

---

## ✅ Contribution Guidelines

- **No malware.** All tools must be for educational/research use only.
- **Include a brief description** of what your script or tool does — either in a comment header or a small `README.md` inside the folder.
- **Test your scripts** before submitting. Broken or untested code won't be merged.
- **No duplicate tools.** Check existing folders first.
- **Frida scripts** should include a comment block at the top with: target (e.g. OkHttp3), tested Android version, and a short description.

---

## 📝 Frida Script Header Template

```javascript
/**
 * Script:      SSL Pinning Bypass (OkHttp3)
 * Author:      yourname
 * Tested on:   Android 12, Android 13
 * Description: Bypasses certificate pinning on apps using OkHttp3.
 * Usage:       frida -U -f com.target.app -l ssl-bypass-okhttp3.js
 */
```

---

## ⚠️ Disclaimer

All contributions must follow the repo's [educational-use-only](LICENSE.txt) policy. Do not submit tools intended for illegal or malicious activity. Contributors are responsible for their own submissions.

---

## 💬 Questions?

Open an issue or reach out via the existing GitHub Issues tab.

Made with 💻 by [jcrvnx](https://github.com/jcrvnx)
