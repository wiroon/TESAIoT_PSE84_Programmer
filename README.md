# TESAIoT PSE84 Programmer

**Flash your PSoC™ Edge E84 board in three clicks — no command line, no toolchain, no fuss.**

TESAIoT PSE84 Programmer is a lightweight desktop app that turns firmware flashing into a simple, friendly experience. Plug in your board, pick a firmware image, and press Flash. That's it.

---

## Why you'll like it

- **Plug-and-play detection** — the app recognizes your board the moment you connect it and shows you exactly what's attached.
- **One-click local flashing** — choose a firmware file and program your board over USB. Real-time progress keeps you informed every step of the way.
- **Flash from anywhere** — pair with a web session using a one-time code and program a board remotely, perfect for classrooms, labs, and distributed teams.
- **Clean, focused interface** — no clutter, no jargon. Everything you need on one screen.
- **Cross-platform** — the same simple app on macOS (Apple Silicon & Intel), Windows, and Linux.

---

## Download

Open the **[Releases](../../releases)** page and download the installer that matches your operating system:

| Platform | File |
|---|---|
| 🍎 macOS (Apple Silicon & Intel) | `..._universal.dmg` |
| 🪟 Windows 10 / 11 | `..._x64-setup.exe` or `..._x64_en-US.msi` |
| 🐧 Linux (Debian / Ubuntu) | `..._amd64.deb` |
| 🐧 Linux (RHEL / Fedora) | `....x86_64.rpm` |
| 🐧 Linux (any distro) | `..._amd64.AppImage` |

---

## Install

### macOS

1. Open the `.dmg` and drag **TESAIoT PSE84 Programmer** into your **Applications** folder.
2. **First launch:** right-click the app and choose **Open**, then confirm you trust it.
   This is needed because the app is not yet notarized with Apple — it's safe to run, you only confirm it once.

### Windows

1. Run the `.exe` or `.msi` installer and follow the prompts.
2. **First launch:** Windows may show a **"Windows protected your PC"** banner. Click **"More info"** and then **"Run anyway"**.
   This is shown because the installer isn't yet signed with an extended-validation certificate — it's safe to run, you only confirm it once.

### Linux

Pick the package that matches your distribution and install with your usual package manager. Examples:

```bash
# Debian / Ubuntu
sudo apt install ./TESAIoT_PSE84_Programmer_0.2.0_amd64.deb

# Fedora / RHEL
sudo dnf install ./TESAIoT_PSE84_Programmer-0.2.0-1.x86_64.rpm

# AppImage (no install — just run)
chmod +x TESAIoT_PSE84_Programmer_0.2.0_amd64.AppImage
./TESAIoT_PSE84_Programmer_0.2.0_amd64.AppImage
```

---

## System requirements

- A **PSoC™ Edge E84** development board with an on-board KitProg3 programmer
- A USB cable to connect the board to your computer
- **macOS 12+**, **Windows 10/11**, or a modern Linux distribution

---

## Getting started

1. Connect your board to your computer with a USB cable.
2. Launch **TESAIoT PSE84 Programmer** — your board is detected automatically.
3. Pick **Local** to flash a firmware file from your computer, or **Remote** to flash using a pairing code.
4. Press **Flash** and watch the progress bar do the work.

---

## Support

Found something that could be better? Open an issue on the **[Issues](../../issues)** tab and we'll take a look.

---

© TESAIoT · Thailand Embedded Systems Association
