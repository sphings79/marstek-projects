# Marstek projects

Tools, firmware research and Home Assistant integrations for Marstek Venus, Saturn and CT002 battery storage. Unofficial, not affiliated with Marstek.

[Deutsch](README.de.md)

## Home Assistant

| Project | Description |
|---|---|
| [Marstek Modbus Suite](https://github.com/sphings79/marstek-modbus-suite) | Home Assistant integration for Marstek Venus A, D, E over local Modbus TCP — sensors, controls, schedules, full register map. No cloud. |

## Control and bridge

| Project | Description |
|---|---|
| [Marstek BLE Control](https://github.com/sphings79/marstek-ble-control) | Cloud-free web control panel for Venus A / D / E over Web Bluetooth — OTA updates, peak shaving, local Modbus TCP / Shelly Pro 3EM setup. |
| [Marstek BLE Bridge](https://github.com/sphings79/marstek-ble-bridge) | ESP32 bridge that relays the Venus Bluetooth LE link over a WebSocket and serves the BLE Control web app. |
| [Marstek Offline Endpoint](https://github.com/sphings79/Marstek-offline-endpoint) | Self-hosted container that answers the Venus telemetry upload locally — stops the 30-minute network resets. |

## Firmware

| Project | Description |
|---|---|
| [Marstek Firmware Archive](https://github.com/sphings79/marstek-firmware-archiv) | Firmware archive for Venus E, D, A, Saturn/B2500 and CT002 — OTA downloads, release notes, SHA-256 checksums. |
| [Marstek Venus Firmware Reverse Engineering](https://github.com/sphings79/Marstek-Venus-Firmware-Reverse-Engineering) | Static reverse engineering of the Venus firmware with Ghidra — Modbus TCP and RS485 register map, protocol notes, scan tools. |

## More overviews

- [Home Assistant projects](https://github.com/sphings79/home-assistant-projects)
- [Apps](https://github.com/sphings79/apps)

- [sphings-dev.de](https://sphings-dev.de/)
