# Vessel Motion OTA

Public firmware and dashboard artifacts for manual Vessel Motion updates.

- `manifest.json` describes the current WT32-ETH01 firmware.
- `firmware.bin` is downloaded only after the user presses **UPDATE** in Settings.
- `littlefs.bin` contains the matching dashboard files.
- The device verifies the board ID, version, byte size, HTTPS certificate, and MD5 before activating each update.

For releases that update both firmware and dashboard files, press **UPDATE** once to install and restart the firmware, then press **UPDATE** again to install and restart the dashboard.

Updates are never checked or installed automatically.
