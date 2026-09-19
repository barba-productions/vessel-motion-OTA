# Vessel Motion OTA

Public firmware artifacts for manual Vessel Motion updates.

- `manifest.json` describes the current WT32-ETH01 firmware.
- `firmware.bin` is downloaded only after the user presses **UPDATE** in Settings.
- The device verifies the board ID, version, byte size, HTTPS certificate, and MD5 before activating an update.

Updates are never checked or installed automatically.
