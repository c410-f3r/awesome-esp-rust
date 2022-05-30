# Awesome ESP Rust

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of resouces for development in the Rust programming language for ESP32, ESP32-C3, ESP32-S2, and ESP32-S3.

## Table of Contents

- [Community](#community)
- [Books, Blogs, and Training Materials](#books-blogs-and-training-materials)
- [Tools](#tools)
- [Templates](#templates)
- [Open Hardware](#open-hardware)
- [Projects](#projects)
- [License](#license)

## Community

You can usually find community members (including some employees of Espressif) in the [`#esp-rs:matrix.org` Matrix room](https://matrix.to/#/#esp-rs:matrix.org).

## Books, Blogs, and Training Materials

- [The Rust on ESP Book](https://esp-rs.github.io/book/introduction.html) - The goal of this book is to provide a comprehensive guide on using the Rust programming language with Espressif SoCs and modules.
- [Embedded Rust on Espressif](https://espressif-trainings.ferrous-systems.com/) - Training for Rust development on ESP32-C3 by [Ferrous Systems](https://ferrous-systems.com/training/).

## Tools

- [espflash](https://github.com/esp-rs/espflash) - Serial flasher utility for Espressif SoCs and modules based on [esptool](https://github.com/espressif/esptool).
- [esp-web-flash-server](https://github.com/bjoernQ/esp-web-flash-server) - WebSocket server for flashing from Visual Studio Code Remote Containers using a web browser.
- [wokwi-server](https://github.com/MabezDev/wokwi-server) - WebSocket server for running simulations in [Wokwi](https://wokwi.com/) from Visual Studio Code Remote Containers using a web browser.

## Templates

- [esp-idf-template](https://github.com/esp-rs/esp-idf-template) - A [cargo-generate](https://cargo-generate.github.io/cargo-generate/) template for projects using the Rust `std` library (via [ESP-IDF](https://github.com/espressif/esp-idf)).
- [esp-template](https://github.com/esp-rs/esp-template) - A [cargo-generate](https://cargo-generate.github.io/cargo-generate/) template for bare metal projects (ie. `no_std`).

## Open Hardware

- [esp-rust-board](https://github.com/esp-rs/esp-rust-board) - A development board based on the ESP32-C3 and designed in [KiCad EDA](https://www.kicad.org/) which is compatible with the [Adafruit Feather](https://learn.adafruit.com/adafruit-feather/feather-specification) specification.

## Projects

- [esp32c3-rust-std-temperature-logger](https://github.com/bjoernQ/esp32c3-rust-std-temperature-logger) - Demo of Rust on ESP32-C3 (using [ESP-IDF](https://github.com/espressif/esp-idf)) with MQTT and [adafruit.io](https://io.adafruit.com/) for temperature logging.
- [rust-esp32-std-demo](https://github.com/ivmarkov/rust-esp32-std-demo) - A demo `std` binary crate for the ESP32[XX] and [ESP-IDF](https://github.com/espressif/esp-idf), which connects to WiFi, Ethernet, drives a small HTTP server and draws on a LED screen.
- [rustzx-esp32](https://github.com/georgik/rustzx-esp32) - ZX Spectrum emulator based on RustZX project.
- [wrover-experimental](https://github.com/JurajSadel/wrover-experimental) - Display line directions and departure times of public transport vehicles in Brno, CZ.

## License

This list is licensed under

- CC0 1.0 Universal License ([LICENSE](LICENSE) or https://creativecommons.org/publicdomain/zero/1.0/legalcode)
