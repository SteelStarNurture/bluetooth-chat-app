# Bluetooth Chat App

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0082FC,100:001B44&height=220&section=header&text=Bluetooth%20Chat%20App&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Communicate%20Offline%20Without%20Wi-Fi%20Or%20Cellular%20Data&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.0.2-001B44?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-96.3K-0082FC?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

---

## 📡 The End Of Dead Zones

We live in a hyper-connected world, yet we still find ourselves in dead zones. Subways, airplanes, camping trips, and crowded stadiums often have zero cellular reception. And when the Wi-Fi goes down, your ability to communicate goes down with it.

**Bluetooth Chat App** is a powerful, open-source Android application that allows you to send text messages and files to nearby devices using only Bluetooth. No internet. No cell towers. No data plans. Just pure, peer-to-peer communication.

This repository provides the complete Android source code, including the Bluetooth discovery engine, the secure socket layer, and a beautiful, modern Material Design UI. It is the ultimate tool for hikers, travelers, and anyone who needs to communicate when the grid goes down.

<img width="1670" height="941" alt="0e7abef8-eaf4-4089-830b-98346e46bf99" src="https://github.com/user-attachments/assets/3b72e56d-c1aa-4ba1-9b18-1cc4e78063dc" />

---

## 🏗️ The Three Layers Of The App

We have structured the application to be fast, reliable, and incredibly easy to use.

| Layer | Description | Technology |
| :--- | :--- | :--- |
| **Discovery** | Finds nearby Bluetooth devices | Android Bluetooth API |
| **Connection** | Establishes a secure socket connection | RFCOMM Socket |
| **Messaging** | Sends and receives text and files | Java, Kotlin |

---

## ✨ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Offline Messaging** | Send text messages without any internet connection |
| **File Transfer** | Share photos, documents, and music directly |
| **Group Chat** | Create a local mesh network with multiple devices |
| **No Data Usage** | Zero cellular data or Wi-Fi required |
| **Modern UI** | A beautiful, dark-themed Material Design interface |
| **Open Source** | Fully transparent, community-driven, and free to use |

---

<div align="center">

### 🔗 Ready to chat offline?

[![Get App](https://img.shields.io/badge/📡_GET_APP-0082FC?style=for-the-badge&logoColor=white)](https://share.google/gEHDXkFZiyTM8RGon)

</div>

---

## ⚙️ Quick Setup

You will need Android Studio and a device running Android 8.0+.

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/bluetooth-chat-app.git

# Step 2: Open the project in Android Studio
# Step 3: Build the APK
./gradlew assembleDebug

# Step 4: Install the APK on your device
adb install app/build/outputs/apk/debug/app-debug.apk
```

Once installed, open the app. It will automatically scan for nearby devices. Tap on a device to connect. Once connected, you can start sending messages and files immediately.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-001B44?style=for-the-badge&logoColor=white)](https://share.google/gEHDXkFZiyTM8RGon)

</div>

---

## 🧠 Under The Hood: The RFCOMM Protocol

How does Bluetooth chat actually work? It uses a protocol called **RFCOMM**.

RFCOMM is a simple, reliable data stream protocol based on the ETSI TS 07.10 standard. It emulates a serial port over the Bluetooth connection. It is the standard protocol for Bluetooth serial communication.

When you connect to a device, your phone creates a socket. The RFCOMM protocol handles the packetization, error correction, and flow control. It ensures that your messages arrive in the correct order, even if the connection is briefly interrupted. It is the same protocol used by Bluetooth headsets, printers, and car kits.

---

## 🛠️ Tech Stack

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Bluetooth](https://img.shields.io/badge/Bluetooth-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![RFCOMM](https://img.shields.io/badge/RFCOMM-000000?style=flat-square&logo=bluetooth&logoColor=white)
![Jetpack](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We believe that communication should not be limited by infrastructure. If you have found a bug in the discovery engine, improved the UI, or want to add support for a new feature, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-feature`).
3. **Commit** your changes (`git commit -m 'Add new feature'`).
4. **Push** to the branch (`git push origin feature/new-feature`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your setups, ask for help with Bluetooth permissions, and discuss the latest trends in offline communication.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@bluetooth-chat.dev.

---

<div align="center">

### ⭐ If this app keeps you connected, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/bluetooth-chat-app)

---

### 🚀 Start chatting today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-3DDC84?style=for-the-badge&logoColor=white)](https://share.google/gEHDXkFZiyTM8RGon)

<sub>Crafted with precision and ❤️ by the Bluetooth Chat App community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:001B44,100:0082FC&height=120&section=footer)

</div>