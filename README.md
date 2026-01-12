# 🔐 SSL Pinning Bypass Instagram App

Instagram SSL Pinning Bypass and intercept Instagram Traffic.

---

## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/7bc072e2-331d-4550-9c40-38243d00bfbe" />

[▶️ Watch Demonstration](https://github.com/user-attachments/assets/c3bb3f56-48cd-4a80-8826-9f5f4848b157)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Instagram App Version 
- **411.0.0.23.257**
---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)


## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator


## 🚀 Bypass Procedure

1. Replace patched `libstartup.so with /data/data/com.instagram.android/lib-compressed/libstartup.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libstartup.so /data/data/com.instagram.android/lib-compressed/libstartup.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libcoldstart.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
