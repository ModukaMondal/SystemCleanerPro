# System Cleaner Pro v5.0.0 🚀

**System Cleaner Pro** is a powerful, cross-platform system optimization and maintenance utility built with Python and a modern Tkinter graphical user interface. Designed for both Windows and Linux environments, it provides deep system cleaning, privacy tools, storage management, and advanced automation to keep your operating system running at peak performance.

---

## 🌟 What's New in v5.0.0 (Key Features & Upgrades)

Version 5.0.0 introduces several breakthrough modules and security enhancements, expanding far beyond standard cleanup utilities:

* **🧩 Browser Extensions Manager (`browser_extensions.py`)**: Safely inspect, audit, manage, and clean installed browser extensions and plugins across supported web browsers.
* **🔒 Secure Drive Wiper (`drive_wiper.py`)**: Advanced cryptographic and secure wiping utilities designed to permanently erase residual data and unallocated space, ensuring complete privacy.
* **🎬 Filmora & Media Cache Cleaner (`filmora_cleaner.py`)**: Dedicated high-performance cache and temporary file cleanup module specifically targeting heavy video editing suites like Wondershare Filmora and media render caches.
* **📂 Advanced Storage Explorer (`storage_explorer.py`)**: Deep-dive disk space analyzer that categorizes large directories, hidden logs, and redundant files, giving users granular control over local storage.
* **✍️ Enterprise-Grade Code Signing**: Windows binaries (`.exe`) are now digitally signed with a validated self-signed code-signing certificate (`Status: Valid`), ensuring executable integrity and trust.
* **🛡️ Robust QA Test Framework**: Expanded automated QA test suites covering cross-platform regression, memory stability, UI state persistence, and feature integration tests.

---

## 🛠️ Core Features (Carried Over & Optimized from v4.x)

* **🧹 Comprehensive System Cleaner**: Scans and flushes temporary directories, system logs, application caches (including AutoCAD and general temp files), and browser caches.
* **📦 Bulk Software Uninstaller (`bulk_uninstaller.py`)**: Streamlines the removal of unwanted applications and lingering registry/directory residues.
* **📋 Clipboard Monitor & Manager (`clipboard_monitor.py`)**: Securely tracks and manages clipboard history with options for quick clearing and privacy protection.
* **⚙️ Advanced System Tools (`advanced_tools.py`)**: Includes background RAM optimization, CPU performance profiles, disk defragmentation, and SSD TRIM maintenance support.
* **🔄 Cross-Platform Architecture**: Seamlessly compiled and native-supported on both **Windows 11** (via batch scripts) and **Linux / WSL2 Ubuntu** (via shell automation scripts).

---

## 📂 Project Directory Structure

```text
System_Cleaner_Pro_v5.0.0/
├── system_cleaner_pro.py        # Main Application Core & GUI
├── advanced_tools.py            # Advanced System Optimization Modules
├── bulk_uninstaller.py          # Bulk Application Uninstaller
├── clipboard_monitor.py         # Clipboard Activity Tracker
├── browser_extensions.py        # Browser Extension & Plugin Manager
├── drive_wiper.py               # Secure Drive & Free Space Wiper
├── filmora_cleaner.py           # Media Cache & Filmora Cleaner
├── storage_explorer.py          # Deep Storage & Disk Space Explorer
├── qa_*.py                      # Comprehensive Automated QA Test Suites
├── build_linux.sh               # Linux Build & Environment Automation
├── build_windows.bat            # Windows PyInstaller Compilation Script
├── sign_windows.bat             # Windows Digital Code-Signing Script
└── README.md                    # Project Documentation