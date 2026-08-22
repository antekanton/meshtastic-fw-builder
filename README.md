# Meshtastic Heltec RU Firmware

[English](#english) | [Русский](#русский)

---

## English

### Overview

Stable Meshtastic firmware builds for Heltec boards with Russian language support and RU power limits (30 dBm).

### Supported Devices

- **Lilygo T3S3 E-Paper** (ESP32-S3)
- **Heltec V4 OLED** (ESP32-S3)
- **Heltec V3** (ESP32-S3)
- **Heltec Mesh Node T114** (nRF52840)
- **Heltec Mesh Node T096** (nRF52840)

### Features

- ✅ Russian language interface
- ✅ RU region power limit (30 dBm)
- ✅ Automated builds on every upstream release
- ✅ Pre-compiled binaries with SHA256 checksums

### Installation

1. Download the firmware `.bin` file for your board from [Releases](https://github.com/antekanton/meshtastic-fw-builder/releases)
2. Flash using [Web Flasher](https://flasher.meshtastic.org/) or `esptool`/`nrfutil`
3. Configure region to **RU** in the Meshtastic app

### Build

This repository uses GitHub Actions to automatically build firmware when a new Meshtastic release is published. Manual trigger available via `workflow_dispatch`.

---

## Русский

### Обзор

Стабильные сборки прошивки Meshtastic для плат Heltec с поддержкой русского языка и региональными ограничениями мощности для RU (30 dBm).

### Поддерживаемые устройства

- **Lilygo T3S3 E-Paper** (ESP32-S3)
- **Heltec V4 OLED** (ESP32-S3)
- **Heltec V3** (ESP32-S3)
- **Heltec Mesh Node T114** (nRF52840)
- **Heltec Mesh Node T096** (nRF52840)

### Возможности

- ✅ Русский язык интерфейса
- ✅ Ограничение мощности для региона RU (30 dBm)
- ✅ Автоматическая сборка при каждом релизе upstream
- ✅ Готовые бинарники с SHA256-чексуммами

### Установка

1. Скачайте файл прошивки `.bin` для вашей платы из [Releases](https://github.com/antekanton/meshtastic-fw-builder/releases)
2. Прошейте через [Web Flasher](https://flasher.meshworks.ru/) или `esptool`/`nrfutil`
3. В приложении Meshtastic установите регион **RU**

### Сборка

Этот репозиторий использует GitHub Actions для автоматической сборки прошивки при каждом новом релизе Meshtastic. Ручной запуск доступен через `workflow_dispatch`.

---

## License / Лицензия

This project is based on [Meshtastic firmware](https://github.com/meshtastic/firmware). See upstream license for details.

Проект основан на [прошивке Meshtastic](https://github.com/meshtastic/firmware). Подробности в лицензии upstream.