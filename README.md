# Tetherline

Connects your Windows PC to the internet through the **mobile data** of an Android phone plugged in over USB.
No proxy settings: every program on the PC just works.

This repository is **only for distributing the PC app**. The source code is not public.

## Download

Get the latest `Tetherline-<version>-win-x64.zip` from [**Releases**](../../releases/latest).
Use the `.sha256` file next to it to verify your download.

Install the phone app from Google Play. (Coming soon)

## Requirements

- Windows 10 (64-bit) or Windows 11, with administrator rights
- An Android 8.0+ phone with USB debugging turned on and the Tetherline app installed
- A USB cable that carries data

## How to use

1. Unzip to any folder.
2. Right-click `allow-firewall.bat` and choose **Run as administrator**. (First time only)
3. Connect the phone over USB and tap **Start relay** in the phone app.
4. Run `Tetherline.exe`. When the taskbar icon turns green, you are connected.

See `README.txt` inside the zip for details.

## Good to know

- The app is not code-signed yet, so the first run may show "Windows protected your PC". Click **More info → Run anyway**.
- It will not run on PCs with Smart App Control turned on.
- ping (ICMP) does not work.

## Reporting problems

Open an [issue](../../issues) with your Windows version, phone model, and the log copied from the tray icon menu via **Show log → Copy all**.

## Links

- [App page](https://thetann.github.io/apps/tetherline/)
- [Privacy policy](https://thetann.github.io/apps/tetherline/privacy/)
