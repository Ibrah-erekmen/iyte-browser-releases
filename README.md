# IYTE Browser

Secure exam browser for the programming labs of the
**Department of Electrical and Electronics Engineering, Izmir Institute of Technology**.

## Download

**[Latest version →](https://github.com/Ibrah-erekmen/iyte-browser-releases/releases/latest)**

| Your computer | File |
| --- | --- |
| **Mac with Apple Silicon** – M1, M2, M3, M4 or newer | `IYTE-Browser-<version>-mac-arm64.dmg` |
| **Mac with Intel processor** | `IYTE-Browser-<version>-mac-x64.dmg` |
| **Windows 10 / 11** | `IYTE-Browser-<version>-win.exe` |
| **Linux** – Ubuntu / Debian | `IYTE-Browser-<version>-linux-amd64.deb` |
| **Linux** – other distributions | `IYTE-Browser-<version>-linux-x86_64.AppImage` |

**Which Mac do I have?** Apple menu → **About This Mac**. "Chip: Apple M…" means Apple Silicon; "Processor: Intel" means Intel.

Installation steps are in `IYTE-Browser-Student-Guide.pdf`, attached to every release.

- **macOS:** the app is not registered with Apple. After moving it to Applications, run once in Terminal:
  `xattr -dr com.apple.quarantine "/Applications/IYTE Browser.app"`
- **Windows:** if SmartScreen appears, choose **More info → Run anyway**.

## Updates

IYTE Browser tells you on its start screen when a new version is published here.
Install the new version over the old one.

## Check your download

Every release includes `SHA256SUMS.txt`. Compare it with:
macOS/Linux `shasum -a 256 <file>`, Windows `certutil -hashfile <file> SHA256`.
Only install IYTE Browser from this page or from your course page.

---

This repository only holds the installers. Questions: ask your lab instructor or assistants.
