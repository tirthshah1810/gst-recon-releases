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

## Download for Mac (Apple Silicon and Intel, macOS 11 or later)

- [GST-Recon-macOS.dmg](https://github.com/tirthshah1810/gst-recon-releases/releases/latest/download/GST-Recon-macOS.dmg)

1. Open the downloaded `GST-Recon-macOS.dmg` and drag **GST Recon** into **Applications**.
2. Open GST Recon from Applications. The first time, macOS says it cannot verify the developer, because the app is not
   yet notarised by Apple. Click **Done** (or **OK**).
3. Open **System Settings → Privacy & Security**, scroll down to the message about GST Recon and click **Open Anyway**,
   then confirm with your Mac password. From then on it opens normally.

## Your data

Everything stays on the computer. The database and its weekly backups are in
`C:\Users\<you>\AppData\Roaming\in.gstrecon.desktop\` on Windows and
`~/Library/Application Support/in.gstrecon.desktop/` on a Mac. Use **Settings and backup → Back up now** to keep a copy elsewhere.
