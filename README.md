<p align="center">
  <img src="assets/banner.png" alt="RigKeeper" width="100%">
</p>

<p align="center">
  <img src="assets/icon.svg" alt="RigKeeper icon" width="96">
</p>

<h1 align="center">RigKeeper</h1>

<p align="center">
  <b>Keep your Windows PC fresh, stable and game-ready — for free.</b><br>
  Drivers, game components, program updates and system health in one clean, no-nonsense app.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?logo=windows&logoColor=white" alt="Platform">
  <img src="https://img.shields.io/badge/price-free-2ea44f" alt="Free">
  <img src="https://img.shields.io/badge/status-pre--1.0-orange" alt="Status">
  <img src="https://img.shields.io/github/v/release/Siano1987/RigKeeper?include_prereleases&label=release" alt="Release">
  <img src="https://img.shields.io/github/downloads/Siano1987/RigKeeper/total?label=downloads" alt="Downloads">
  <img src="https://img.shields.io/badge/languages-7-8A2BE2" alt="7 languages">
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇️ Download the latest version</b></a>
  &nbsp;·&nbsp;
  <a href="https://www.paypal.com/qrcodes/p2pqrc/4WHWH3RRY8G9J"><b>☕ Buy me a coffee</b></a>
</p>

<p align="center">
  <img src="assets/demo.gif" alt="RigKeeper – one-click PC check" width="900">
</p>

---

## ✨ Why RigKeeper?

Most "driver booster" tools are packed with ads, upsells and paywalled features.
**RigKeeper** does the useful part — finding outdated drivers, missing components and real problems on your PC —
and nothing else. No subscriptions, no "PRO" nag screens, no bundled junk.

And it goes a step further than the usual updaters: it **watches what happens after an update** and lets you
roll back a driver that made your PC less stable.

## 🚀 Features

- 🩺 **One-click PC check** – drivers, graphics card, game components, programs, disks, battery and system crashes in a single scan,
  with a **0–100 score** and a to-do list where every item has a button that fixes it
- 🔍 **Driver updates** – finds outdated, missing or faulty drivers and installs **certified, digitally signed drivers
  published by hardware manufacturers**; one driver or all of them at once
- 🖥️ **Graphics drivers straight from the vendor** – the latest **NVIDIA** driver downloaded from nvidia.com and installed
  silently (optional clean install); official tools for **AMD** and **Intel**
- 🎮 **Game components** – Visual C++ Redistributables, DirectX, .NET, XNA, OpenAL, PhysX, WebView2 and Vulkan,
  installed from official packages (PhysX is offered only on PCs with an NVIDIA card)
- 📦 **Program updates** – finds newer versions of your installed programs (7-Zip, VLC, Notepad++, Git…) in Microsoft's
  official package catalog and updates them silently; ignore the ones you want to keep as they are
- 🛡️ **Stability Guard** – saves your current driver before every update and watches the system log for 7 days
  (blue screens, unexpected shutdowns, graphics driver hangs). If things get worse, **roll back with one click**
- 🔧 **Fix device errors** – finds devices with an error in Device Manager (missing driver, code 43, disabled device…)
  and fixes them in one click: enables, restarts or reinstalls the device and tells you what it did
- 🧹 **Clean up unused devices** – removes leftovers of old USB drives, disks, mice and other hardware
  that is no longer connected (system entries are left alone by default)
- 💾 **Reinstall Kit** – put your drivers, game components, program list and settings on a USB drive and restore
  everything after reinstalling Windows
- 📋 **PC health report** – disk condition, free space, battery wear, recent crashes and antivirus status,
  exportable as an HTML report (handy for a repair shop)
- ⏪ **Safe by default** – a restore point before changes, driver backups, full history of every operation
- 🔔 **Runs quietly in the background** – tray icon, notifications and optional scheduled checks
- 🔄 **Signed automatic updates** – every new version is verified with a digital signature before it is installed
- 🌙 **Dark & light mode** – follows your Windows theme automatically
- 🌍 **7 languages** – English, Polski, Deutsch, Français, Español, Українська, Nederlands (picked automatically)
- 💸 **100% free** – no ads, no trials, no hidden paywall

## 📸 Screenshots

<picture>
  <source media="(prefers-color-scheme: light)" srcset="assets/screenshots/scan-light.png">
  <img src="assets/screenshots/scan.png" alt="Scan – score and to-do list">
</picture>

<p align="center">
  <img src="assets/screenshots/drivers.png" alt="Driver updates" width="49%">
  <img src="assets/screenshots/graphics-card.png" alt="Graphics card" width="49%">
</p>
<p align="center">
  <img src="assets/screenshots/components.png" alt="Game components" width="49%">
  <img src="assets/screenshots/stability-guard.png" alt="Stability Guard" width="49%">
</p>
<p align="center">
  <img src="assets/screenshots/programs.png" alt="Program updates" width="49%">
  <img src="assets/screenshots/tools.png" alt="Tools – repair and cleanup" width="49%">
</p>
<p align="center">
  <img src="assets/screenshots/fix-device-errors.png" alt="Fix device errors" width="49%">
  <img src="assets/screenshots/tools-light.png" alt="Light mode" width="49%">
</p>
<p align="center">
  <img src="assets/screenshots/reinstall-kit.png" alt="Reinstall Kit" width="49%">
  <img src="assets/screenshots/welcome.png" alt="Start screen" width="49%">
</p>

## 📦 Download

Grab the latest build from the [**Releases**](../../releases/latest) page, run `RigKeeper_Setup_x.y.exe` and you're good to go.
Once installed, RigKeeper updates itself.

> ⚠️ RigKeeper is still **before version 1.0**. It works, but expect rough edges.
> Bug reports are very welcome!
>
> Windows SmartScreen may warn you about an unknown publisher — the installer is not code-signed yet.
> Click **More info → Run anyway**.

### Requirements

- Windows 10 or Windows 11 (64-bit)
- Administrator rights (needed to install drivers)
- Internet connection

## 🔒 Privacy

RigKeeper does **not** collect or send any personal data, usage statistics or telemetry.
It only connects to the internet to check for its own updates (GitHub), to download drivers and components
from their manufacturers (e.g. NVIDIA, Microsoft) and to search for drivers through Windows.

## 🛠️ How it works

1. **Check** – one click reads your devices, drivers, graphics card, installed components and programs, disks, battery and the system log.
2. **Review** – you get a score and a short to-do list: what's outdated, missing or broken, and why it matters.
3. **Fix** – you choose what to update or repair; a restore point and a backup of the current driver are created first.
4. **Watch** – for the next 7 days Stability Guard checks that the new drivers behave. If not, roll back with one click.

## 🗺️ Roadmap

- [x] Driver scan & update
- [x] Dark mode
- [x] Game components manager
- [x] Scheduled background checks
- [x] Driver backup & restore
- [x] Graphics drivers straight from NVIDIA
- [x] Stability Guard (automatic rollback suggestions)
- [x] Reinstall Kit (USB)
- [x] PC health score & report
- [x] Signed automatic updates
- [x] Fix device errors & clean up unused devices
- [x] Program updates
- [ ] Code-signed installer
- [ ] Available via `winget`
- [ ] **Stable 1.0 release**

## 🐞 Reporting issues

Found a bug or a driver that won't update? [Open an issue](../../issues) and include:
- your Windows version,
- the device / driver in question,
- a screenshot or the log file, if possible (logs are in `%APPDATA%\RigKeeper\logi`).

## ☕ Support

RigKeeper is free and always will be. If it saved you some time, you can buy me a coffee — thank you!

<p>
  <a href="https://www.paypal.com/qrcodes/p2pqrc/4WHWH3RRY8G9J">
    <img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-PayPal-FFDD00?style=for-the-badge&logo=paypal&logoColor=black" alt="Buy me a coffee via PayPal">
  </a>
</p>

<details>
<summary><b>Crypto</b> (BTC · ETH · USDT TRC-20)</summary>
<br>

| | Network | Address |
|---|---|---|
| <img src="assets/support/btc.png" width="110" alt="BTC QR"> | **Bitcoin (BTC)** | `bc1qtxed92cmpf62em3xu06lcshtxm8g9nuydv2rvj` |
| <img src="assets/support/eth.png" width="110" alt="ETH QR"> | **Ethereum (ETH)** – ERC-20 only | `0x3f402e2a2e1DB1aCCE1b5aAF8f11a29937599c27` |
| <img src="assets/support/usdt.png" width="110" alt="USDT QR"> | **Tether (USDT)** – TRON (TRC-20) only | `TGVWRMR7VhTrHrFqUsZYpxkHoDS5ogVsjr` |

Please send only on the network listed next to each address.
</details>

You'll also find the ☕ button right in the app.

## 📄 License

RigKeeper is **freeware** – free to use at home and at work, free to share in its original form.
See [LICENSE](LICENSE) for the full terms.
RigKeeper is built with open-source components (Qt / PySide6 under LGPL-3.0, Python, cryptography) –
see [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Drivers installed by RigKeeper belong to their manufacturers.

---

<p align="center">
  Made with ☕ by <b>Siano</b> · <a href="mailto:siano19@gmail.com">siano19@gmail.com</a>
</p>
