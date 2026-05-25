# Mobile Security Lab – Android Security Analysis using MobSF & DIVA

## Project Overview

This laboratory project demonstrates the setup of a complete Android mobile security testing environment using **MobSF (Mobile Security Framework)** and **DIVA (Damn Insecure and Vulnerable App)**.

The goal of this lab is to analyze a deliberately vulnerable Android application through both **static analysis** and **dynamic analysis** techniques in order to identify common Android security weaknesses.

This environment simulates a real-world mobile application penetration testing workflow commonly used in cybersecurity and Android application security assessments.

---

# Objectives

The main objectives of this lab are:

- Configure an Android testing environment using **Android Virtual Device (AVD)**.
- Deploy **MobSF** using **Docker**.
- Configure communication between MobSF and Android Emulator.
- Install and analyze the **DIVA vulnerable Android application**.
- Perform **static analysis** to identify insecure code patterns.
- Perform **dynamic analysis** to monitor runtime behavior.
- Understand common Android application vulnerabilities.

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| MobSF | Mobile Application Security Analysis |
| Docker | Containerized deployment |
| Android Studio | Emulator management |
| Android Emulator (AVD) | Android testing environment |
| ADB | Android device communication |
| DIVA | Vulnerable Android application |
| PowerShell / Git Bash | Command execution |

---

# Prerequisites

Before starting, ensure the following tools are installed:

### Required Software

- Android Studio
- Docker Desktop
- Git
- Android SDK Platform Tools (ADB)

Verify installations:

```bash
adb version
docker --version
git --version
