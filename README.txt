# SilentUpdate

SilentUpdate is a focused Windows maintenance utility by **ClearByte Systems** that lets you:

- Scan for available Windows updates
- Select only the updates you actually want
- Install them silently inside a daily maintenance window

No more surprise reboots in the middle of work, gaming, or streaming.

---

## ✨ Features

- **Update scan** – Query Windows Update and list available updates with basic details.
- **Selective install** – Choose which updates to install instead of taking everything blindly.
- **Daily maintenance window** – Configure a time window (e.g. 2:00–3:00 AM) when installs are allowed.
- **Silent Scheduled Task** – Uses a Windows Scheduled Task to run installs quietly in the background.
- **Status + logging** – Shows last install result and whether a reboot was required.
- **Clean dark UI** – Minimal, ClearByte-branded interface built with Electron + React + Tailwind.

---

## 🖥️ System requirements

- Windows 10 or Windows 11 (64-bit)
- Administrator privileges (required to manage updates and tasks)
- ~150–250 MB disk space for the installed app

---

## 📦 Download

You can download the latest installer from the **Releases** page:

👉 **[Download SilentUpdate](https://github.com/xKaali/silentupdate-site/releases/latest)**

> If your browser or Windows SmartScreen shows a warning, click **More info → Run anyway**.  
> This is expected for new, unsigned executables from small publishers.

---

## 🚀 Getting started

1. Download and run the installer.
2. Launch **SilentUpdate** from the Start menu.
3. Click **“Scan for updates”** to query available Windows updates.
4. Select the updates you want to install.
5. Configure your **maintenance window** (for example, 2:00–3:00 AM).
6. Click **“Save maintenance window”** – this creates/updates a Windows Scheduled Task.
7. Leave your PC on during that window; SilentUpdate will install updates quietly.

You can also trigger an immediate install from the UI if you prefer to run updates right away.

---

## 🔧 Tech stack

- **Desktop shell:** Electron
- **UI:** React + TypeScript + Tailwind CSS
- **Build tooling:** Vite
- **Packaging:** electron-builder
- **Platform:** Windows 10/11 (x64)

---

## 🗺️ Roadmap

Planned for future versions:

- ✅ Branded ClearByte Systems UI and installer  
- ✅ Dedicated website & direct download link  
- ⬜ System tray icon for quick access  
- ⬜ Auto-check for newer SilentUpdate versions  
- ⬜ More detailed update metadata (KB numbers, categories)  
- ⬜ Optional pre-install restore point creation  
- ⬜ “Pro” features (advanced scheduling, multi-device configs, export/import settings)

---

## 🤝 Contributing

Right now SilentUpdate is a closed, single-publisher utility, but:

- Bug reports and feature suggestions are welcome via **Issues**.
- If you’re interested in contributing code, open an issue describing what you’d like to add.

---

## 💼 Publisher

**ClearByte Systems**  
“Quiet power. Clean control.”

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [`LICENSE`](LICENSE) file for details.
