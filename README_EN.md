# FFBrowser Intelligent Console

[English](./README_EN.md) | [中文](./README.md)

**FFBrowser (FlyFish Intelligent Fingerprint Browser)** is a professional-grade browser platform designed for privacy protection and automation. This repository is the official home for FFBrowser's **Intelligent Console** and **Automation Ecosystem**, providing SDKs, API documentation, and developer tools.

Website: [https://www.ffbrowser.xyz](https://www.ffbrowser.xyz)

## 🌟 Core Features

FFBrowser is not just an anti-detection tool, but a powerful automation infrastructure.

### 🛡️ Hardware-Level Anti-Fingerprinting & Privacy
- **Deep Simulation**: Modifies operating system and hardware environment characteristics, combined with seed value perturbation, to achieve true hardware-level anti-association.
- **Pass Mainstream Detections**: Perfectly passes mainstream fingerprint detection platforms like BrowserScan, Iphey, PixelScan, etc.
- **Local Data Storage**: All data is stored locally and not synced to the cloud, thoroughly protecting user data security.

### 💻 Multi-Platform & Multi-Brand Support
- **Multi-System Simulation**: Supports simulating Windows 10/11, macOS 12-15, Android 10-14 on Windows.
- **Multi-Browser Kernels**: Custom browser brands (Edge, Chrome, Brave, etc.) and version numbers.

### 🤖 Intelligent Console & Automation (Core of this Repo)
- **Local API/SDK**: Provides powerful local HTTP APIs supporting secondary development.
- **Unlimited Calls**: No limits on call frequency or window quantity.
- **Automation Integration**: Easy integration with automation frameworks like Selenium, Puppeteer, Playwright.
- **AI Agent Ready**: A deterministic execution environment designed specifically for AI Agents.

## 🖼️ Product Showcase

The following screenshots demonstrate FFBrowser running on **Windows Server 2012 R2**, successfully simulating **Windows 11** and **macOS 14.4.1** environments and passing mainstream fingerprint detection sites.

<kbd><img src="https://download.ffbrowser.xyz/img/2012R2_1.jpg" width="800" /></kbd>

<kbd><img src="https://download.ffbrowser.xyz/img/2012R2_2.jpg" width="800" /></kbd>

<kbd><img src="https://download.ffbrowser.xyz/img/2012R2_3.jpg" width="800" /></kbd>

## 🚀 Architecture Overview

```text
+--------------------------+
|  Automation Layer / AI   |
|   (SDKs / Python / JS)   |
+------------+-------------+
             |
             | Local HTTP API
             |
+------------v-------------+
|      FFBrowser Core      |
| (Hardware Fingerprint Engine)|
+--------------------------+
```

- **FFBrowser Core**: Runs as a local background service.
- **Local HTTP API**: Automation tools control the browser environment via API.
- **SDKs**: Encapsulate API calls, providing developer-friendly interfaces.

## 🛠️ Quick Start

1. **Download and Install FFBrowser**: [Go to Official Website](https://www.ffbrowser.xyz) (Supports Windows 7+ x64).
2. **Start Service**: Run FFBrowser and ensure the local service is started.
3. **Call API**: Use the provided SDKs or directly call the local API interface to control the browser.

## 📚 Documentation & Resources

- **API Documentation**: Please download and launch the **FFBrowser Client**. The complete Local API documentation is available within the software.
- **Postman Collection**: Import the collection file directly into Postman: [FFBrowser.postman_collection(EN).json](./FFBrowser.postman_collection(EN).json)

## 💰 Pricing

FFBrowser offers flexible subscription models:
- **Monthly**: 30 CNY / 30 Days
- **Yearly**: 300 CNY / 365 Days (18% Off)
- **Includes**: Unlimited window quantity, unlimited API calls, unlimited import/export.
- **Trial**: New users get a free 3-day trial.

## 📞 Contact Us

- **Website**: https://www.ffbrowser.xyz
- **Email**: mp7788414@outlook.com
- **GitHub**: Submit Issues or PRs to contribute.
- **QQ Group**: Group ID: 574418234 (FFBrowser Discussion), or scan code to join

  <img src="https://download.ffbrowser.xyz/img/qcode.jpg" width="300" alt="QQ Group QR Code" />

---
*Note: The FFBrowser core is commercial software, while the SDKs and tools provided in this repository are open source.*
