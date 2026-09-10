# Changelog

## 0.2.2 - 2026-09-10

- Replace the ten-second camera snapshot refresh with Home Assistant's native
  live camera rendering (`camera_view: live`).
- Keep the UniFi Protect medium-resolution camera channel as the default.
- Preserve the active stream during sensor, timer and history updates by
  patching existing DOM nodes instead of rebuilding the full card.
- Use one delegated click handler so controls remain stable after live updates.

## 0.2.1

- Move the camera to the top of the Drift tab and use the full card width.
