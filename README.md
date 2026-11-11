# System Cleaner Pro v4.7.0

**System Cleaner Pro** is an advanced, high-performance system optimization and maintenance utility designed for both **Linux** and **Windows** environments. It features automated temporary file cleanup, live background RAM cleaning, CPU boost capabilities, and system maintenance tools wrapped in a sleek, lightweight graphical interface.

---

## 🚀 What's New in v4.7.0
* **Cross-Platform Support:** Fully optimized builds for modern Linux distributions (via WSL2/Ubuntu) and Windows systems.
* **Isolated Build Pipeline:** Upgraded virtual environment compilation (`venv` with strict dependency handling) ensuring stable binary generation without hardware-specific kernel compilation conflicts (`evdev` decoupled).
* **Enhanced Performance Tools:** Integrated live background memory management, disk defragmentation/TRIM support, and targeted junk file purging (including heavy application caches like AutoCAD).
* **Robust UI Integration:** Full native Tkinter GUI support for seamless user interaction across platforms.

---

## 📂 Project Structure
* `dist/` - Contains the compiled standalone production binaries (`SystemCleanerPro` for Linux / `.exe` for Windows).
* `system_cleaner_pro.py` - Core application source code.
* `bulk_uninstaller.py` - Bulk software removal utility module.
* `clipboard_monitor.py` - Background clipboard tracking and management module.
* `advanced_tools.py` - Advanced system optimization and diagnostic tools.
* `build_linux.sh` - Automated shell script for building the Linux distribution package.

---

## 🛠️ Quick Start & Installation

### For Linux (WSL2 / Ubuntu):
1. Ensure build prerequisites are installed:
   ```bash
   sudo apt update && sudo apt install -y python3-tk python3-dev python3.14-venv build-essential