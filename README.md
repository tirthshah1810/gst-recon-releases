# GST Recon: downloads

Installers for **GST Recon**, an offline desktop app for GST reconciliation (purchases vs GSTR-2B, sales vs GSTR-1,
3B working, open items across months). This repository holds only the installers; the source code is private.

## Download for Windows 10 / 11

**Latest version:** [Releases → Latest](https://github.com/tirthshah1810/gst-recon-releases/releases/latest)

Direct links to the latest version:

- [GST-Recon-Setup-x64.exe](https://github.com/tirthshah1810/gst-recon-releases/releases/latest/download/GST-Recon-Setup-x64.exe) (recommended, installs for the signed-in user)
- [GST-Recon-x64.msi](https://github.com/tirthshah1810/gst-recon-releases/releases/latest/download/GST-Recon-x64.msi) (standard Windows installer)

No GitHub account is needed.

## Installing

1. Run `GST-Recon-Setup-x64.exe`.
2. Windows may show **"Windows protected your PC"** because the app is not code-signed yet. Click **More info**, then **Run anyway**.
3. Follow the installer. GST Recon appears in the Start menu.

The app needs Microsoft Edge WebView2, which Windows 10 and 11 already have; if it is missing, the setup downloads it once.

## Your data

Everything stays on the computer. The database and its weekly backups are in
`C:\Users\<you>\AppData\Roaming\in.gstrecon.desktop\`. Use **Settings and backup → Back up now** to keep a copy elsewhere.
