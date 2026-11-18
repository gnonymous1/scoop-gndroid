# GNDROiD Scoop Bucket

[![Release](https://img.shields.io/github/v/release/gnonymous1/GNDROiD?label=GNDROiD&color=0078D4)](https://github.com/gnonymous1/GNDROiD/releases)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Scoop](https://img.shields.io/badge/Scoop-Compatible-brightgreen.svg)](https://scoop.sh/)

Official third-party [Scoop](https://scoop.sh/) bucket for **GNDROiD** — the next-generation Windows Android virtualization and hardware-bridged emulator suite.

---

## Quick Start

### 1. Add the Bucket
In PowerShell:
```powershell
scoop bucket add gndroid https://github.com/gnonymous1/scoop-gndroid
```

### 2. Install GNDROiD
```powershell
scoop install gndroid
```

### 3. Launch
Once installed, start GNDROiD directly from your terminal or Start menu:
```powershell
gndroid
```

---

## Included Applications

| Application | Command Shims | Start Menu Shortcut | Description |
| :--- | :--- | :--- | :--- |
| **GNDROiD** | `gndroid`, `adb`, `scrcpy` | `GNDROiD Master Suite` | Hardware-bridged Android emulator, multi-instance orchestrator, and 120 FPS wireless phone mirroring. |

---

## Updating & Maintenance

To check for updates and update GNDROiD:
```powershell
scoop update
scoop update gndroid
```

To uninstall GNDROiD:
```powershell
scoop uninstall gndroid
```

To remove the bucket:
```powershell
scoop bucket rm gndroid
```

---

## Requirements
- **OS**: Windows 10 (Build 19041+) or Windows 11 (64-bit)
- **Virtualization**: Windows Hypervisor Platform (WHPX) or Hyper-V enabled
- **Graphics**: GPU supporting Vulkan 1.2+ or DirectX 12
- **Scoop**: Scoop package manager (`irm get.scoop.sh | iex`)

---

## Verification & Integrity
The release archive is cryptographically verified on every release:
- **v2.5.0 SHA256**: `9c87a8d2661e1e46c8571d8b4b0e273a465e0a5ca3ebcf4ad060c583681a194f`
- **Release Source**: [GitHub Releases](https://github.com/gnonymous1/GNDROiD/releases/tag/v2.5.0)

---

## License
Licensed under the [Apache License, Version 2.0](LICENSE).
