# DevNote 1.1.0

DevNote now supports updates from inside the Windows app.

- Settings includes **Check for updates**, an available-version message, and **Download update**.
- Downloads show progress and are verified before installation.
- **Restart to update** installs the downloaded update and relaunches DevNote.
- Unsaved drafts must be saved before restarting. Normal app closes do not install updates automatically.
- Notes, collections, reminders, and settings remain in the same AppData storage.
- GitHub release metadata and installer block maps are included for future updates.

## Install this version once

Version 1.0.0 does not contain the updater. Install **DevNote-Setup-1.1.0-x64.exe** once to enable future in-app updates. Source development mode does not update itself; use the packaged Windows app.

## Downloads

- **DevNote-Setup-1.1.0-x64.exe**: Windows x64 installer, recommended for in-app updates.
- **DevNote-1.1.0-windows-x64.zip**: extract the entire ZIP, then run DevNote.exe.
- **SHA256SUMS.txt**: download checksums.
- **latest.yml** and the installer **.blockmap**: files used by the in-app updater.

Keep the app running or minimized for reminders. This release is not digitally signed.

Source: https://github.com/GianCarlozxc/DevNote (private).

Validation: backend and updater state tests, desktop interaction checks, and checks against the packaged Windows app. Restart tests use a simulated updater to verify saving drafts without installing test updates on the PC.
