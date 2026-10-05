# Class Record

Installers for **Class Record**, the class record and grading app for college instructors. This repository holds releases only.

**[Download the latest version →](https://github.com/elioth-coder/class-record-releases/releases/latest)**

| System | File |
|---|---|
| Windows 10 or 11 (64-bit) | `Class-Record-<version>-windows-x64-setup.exe` |
| macOS on Apple silicon (M1 and later) | `Class-Record-<version>-mac-arm64.dmg` |

Intel Macs are not supported.

## Installing

The installers are not signed yet, so your computer asks once before the first launch.

- **Windows:** run the `.exe`. If Windows says *Windows protected your PC*, click **More info → Run anyway**. It installs for your account only; no administrator rights needed.
- **macOS:** open the `.dmg` and drag **Class Record** to **Applications**. If macOS blocks the first launch, open **System Settings → Privacy & Security** and click **Open Anyway**.

## Activating (from 0.3.0)

Class Record is activated once on each computer:

1. Open Class Record. The activation page shows this computer's **Machine ID**.
2. Click **Copy** and send it to the person who manages your Class Record licenses.
3. Paste the activation key you receive and click **Activate**.

Your records are not touched while Class Record waits for activation, and **File → Back Up…** always works. After replacing a computer's main board or disk, Class Record may ask again: send the new Machine ID for a new key.

## Updating

Class Record checks once a day for a newer version (or use **Help → Check for Updates…**).

1. Click **Download**: the new version downloads in the background with a progress bar. You can keep working.
2. Click **Install now** when it is ready. The installer starts and Class Record closes itself 5 seconds later.
   - **Windows:** follow the installer's steps.
   - **macOS:** in the window that opens, drag **Class Record** onto **Applications** and choose **Replace**.

Your records and backups stay where they are; uninstalling never deletes them either. For extra safety, use **File → Back Up…** before updating. Versions before 0.2.2 open the download in your browser instead: install it as you did the first time. After updating from 0.2.x to 0.3.0, activate as described above.
