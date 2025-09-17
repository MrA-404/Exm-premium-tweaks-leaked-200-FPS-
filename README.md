Here’s a polished **GitHub-ready `README.md`** version of your draft. I formatted it with proper Markdown structure, code blocks, and clean spacing so it looks professional when uploaded:


# EXM Premium Tweaker

**Version:** 0.95  
**Last Updated:** October 29, 2025  
**Author:** [@mra](https://github.com/MrA-404) | **Discord:** mra  

---

## Overview
**EXM Premium Tweaker** is a powerful Windows batch script designed to optimize your PC for gaming and performance. It tweaks system settings, network configurations, CPU/GPU performance, and peripherals to:

- Boost FPS  
- Reduce latency (ping)  
- Improve responsiveness  
- Debloat your system  

Ideal for competitive gamers playing titles like **Fortnite, Valorant**, or other demanding games.

---

## ⚠️ Warning

- Always create a system restore point before applying tweaks (the tool will prompt you).  
- These tweaks modify system settings and registry entries. Test on a secondary setup if unsure.  
- Restart your PC after applying changes for them to take effect.  
- The author is **not responsible for any issues**. Use the built-in restore option to revert if needed.  
- Network tweaks are **Ethernet-only**. WiFi support is planned for v1.0.  

---

## Features

- **System Optimization:** Disable UAC, enable ANSI escape codes, and improve Windows performance.  
- **Network Tweaks:** Reduce ping, bufferbloat, and optimize internet speeds (Ethernet-only).  
- **CPU/GPU Enhancements:** Maximize processor and graphics card performance.  
- **Peripheral Tweaks:** Improve mouse and keyboard responsiveness.  
- **Game-Specific:** Fortnite ping checker and settings optimizer.  
- **Debloat & Cleanup:** Remove bloatware and clean junk files.  
- **Revert & Fixes:** Restore settings or repair corrupted system files.  

---
````markdown
## Installation

### Clone or Download
```bash
git clone https://github.com/MrA-404/Exm-premium-tweaks-leaked-200-FPS-.git
````

Or download **EXMPremiumTweaker.bat** from the [Releases](../../releases) page.

### Run as Administrator

Right-click `EXMPremiumTweaker.bat` → **Run as administrator**.
The script checks for admin privileges and prompts if not elevated.

### Dependencies

* Auto-downloads **NVIDIA Profile Inspector** (if applicable).
* Requires **PowerShell** and **curl** (included in modern Windows).

---

## Usage

1. **Launch:** Run `EXMPremiumTweaker.bat` as administrator.
2. **Create Restore Point:** On first run, select `[1]`.
3. **Navigate the Menu:**

   * Use the colorful CLI interface.
   * Example: Type `2` for Network tweaks, then `1` to disable power-saving features.
4. **Apply Tweaks:** Instant application with confirmation messages.
5. **Exit & Restart:** Type `[X]` and reboot for changes to apply.
6. **Revert Changes:** Use `[S]` for System Restore or `[F]` for specific fixes.

---

## Full Option List

### Main Categories

1. **Windows** – General optimizations (disable UAC, etc.)
2. **Network (Ethernet-only):**

   * `[0]` Reset Network Settings
   * `[1]` Disable Hidden Power Saving Features
   * `[2]` Turn Off Limiting
   * `[3]` Optimize Adapter
   * `[4]` Registry Tweaks
   * `[5]` Disable Nagle’s Algorithm
   * `[6]` Enable Direct Cache Access
   * `[7]` DNS Priority
   * `[8]` Enable Onboard Processor
   * `[9]` Enable MSI Mode
   * `[10]` Disable NetBIOS over TCP/IP
   * `[11]` Network Throttling Index
   * `[12]` Disable WiFi (with revert)
   * `[13]` Optimize Lanman Server
   * `[14]` Adapter Priority
   * `[15]` Advanced Network Tweaks
3. **Power Tweaks** – Performance power plans
4. **Priority Tweaks** – Set process/game priorities
5. **General Tweaks** – RAM, services, misc
6. **BCDEdit** – Boot configuration tweaks
7. **Visual** – Reduce visual effects
8. **Storage** – HDD/SSD optimization
9. **USB Tweaks** – Improve peripheral response
10. **Fix Corrupted Files** – SFC/DISM
11. **RAM Tweaks** – Optimize memory usage
12. **Full Screen Optimization** – Disable FSO in games
13. **GPU Tweaks** – NVIDIA/AMD performance (Profile Inspector)
14. **BIOS Tweaks** – Legacy adjustments (disable Hyper-V, etc.)
15. **CPU Tweaks:**

    * `[1]` Advanced Registry Tweaks
    * `[2–19]` Options for C-states, turbo, idle policies, throttling, etc.
16. **Mouse/Keyboard** – Polling rates & queue sizes
17. **Clean** – Junk/temp file cleanup
18. **DirectX Tweaks** – Game rendering performance
19. **Additional Tweaks** – Misc system performance
20. **Debloat** – Remove pre-installed apps/bloatware
21. **Optimize Games** – Fortnite ping checker & settings optimizer

**Other Menu Options:**

* `E` – Social links (Discord, etc.)
* `F` – Reverts/Fixes
* `R` – Review site
* `S` – Use Restore Point
* `X` – Exit

---

## Recommendations

* **For Gamers:** Start with `Network [2]`, `CPU [15]`, `GPU [13]`, and `Mouse/Keyboard [16]`.
* **Performance Testing:** Use [dslreports.com](https://www.dslreports.com) or [waveform.com](https://www.waveform.com) to measure ping and bufferbloat.
* **Combine Tools:** Works great with **ISLC (Intelligent Standby List Cleaner)**.
* **Ethernet Only:** Avoid applying network tweaks on WiFi until v1.0.
* **Monitor Temps:** Some CPU/GPU tweaks may raise temperatures slightly.

---

## Contributing

We welcome contributions!

1. Fork the repo
2. Create a branch

   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit changes

   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your fork

   ```bash
   git push origin feature/your-feature
   ```
5. Open a Pull Request with details

Ensure compatibility with **Windows 10/11** and avoid breaking existing functionality.

---

## Issues & Support

* **Report Bugs:** Open a GitHub Issue with OS version, error logs, etc.
* **Community Help:** Join the [Discord](https://github.com/MrA-404)
* **Feedback:** Share your experience at [exmtweaks.com/review](https://exmtweaks.com/review)

---

## License

This project is licensed under the **MIT License**. See [LICENSE](./LICENSE) for details.

---

## Credits

* Created by **[@mra](https://github.com/MrA-404)**
* Special Thanks: **@tulantro** for Fortnite optimization help
* Community: [https://github.com/MrA-404](https://github.com/MrA-404)

---

### Happy Tweaking 🚀

```

Do you want me to also design a **badges section** at the top (downloads, version, license, etc.) so it looks like a polished GitHub project page?
```
