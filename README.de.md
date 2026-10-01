# Marstek-Projekte

Werkzeuge, Firmware-Analysen und Home-Assistant-Integrationen für die Batteriespeicher Marstek Venus, Saturn und CT002. Inoffiziell, nicht mit Marstek verbunden.

[English](README.md)

## Home Assistant

| Repo | Beschreibung |
|---|---|
| [marstek-modbus-suite](https://github.com/sphings79/marstek-modbus-suite) | Home-Assistant-Integration für Marstek Venus A, D, E über lokales Modbus TCP — Sensoren, Steuerung, Zeitpläne, volle Register-Map. Ohne Cloud. |

## Steuerung und Brücke

| Repo | Beschreibung |
|---|---|
| [marstek-ble-control](https://github.com/sphings79/marstek-ble-control) | Cloudfreies Web-Bedienfeld für Venus A / D / E über Web Bluetooth — OTA-Updates, Peak Shaving, lokales Modbus TCP / Shelly Pro 3EM. |
| [marstek-ble-bridge](https://github.com/sphings79/marstek-ble-bridge) | ESP32-Brücke, die die Bluetooth-LE-Verbindung des Venus per WebSocket ins Netz bringt und die BLE-Control-Web-App ausliefert. |
| [Marstek-offline-endpoint](https://github.com/sphings79/Marstek-offline-endpoint) | Selbstgehosteter Container, der den Telemetrie-Upload des Venus lokal beantwortet und die 30-Minuten-Netz-Resets stoppt. |

## Firmware

| Repo | Beschreibung |
|---|---|
| [marstek-firmware-archiv](https://github.com/sphings79/marstek-firmware-archiv) | Firmware-Archiv für Venus E, D, A, Saturn/B2500 und CT002 — OTA-Downloads, Release Notes, SHA-256-Prüfsummen. |
| [Marstek-Venus-Firmware-Reverse-Engineering](https://github.com/sphings79/Marstek-Venus-Firmware-Reverse-Engineering) | Statisches Reverse Engineering der Venus-Firmware mit Ghidra — Modbus-TCP- und RS485-Register-Map, Protokollnotizen, Scan-Tools. |

## Weitere Übersichten

- [home-assistant-projects](https://github.com/sphings79/home-assistant-projects)
- [apps](https://github.com/sphings79/apps)

- [sphings-dev.de](https://sphings-dev.de/)
