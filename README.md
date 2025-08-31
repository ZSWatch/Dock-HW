# ZSWatch-Dock

[![License](https://img.shields.io/badge/License-GPL%203.0-blue.svg)](https://opensource.org/license/gpl-3-0/)

## 📑 Table of Contents

- [ZSWatch-Dock](#zswatch-dock)
  - [📑 Table of Contents](#-table-of-contents)
  - [📖 About](#-about)
  - [📂 Directory Breakdown](#-directory-breakdown)
  - [Purchasing](#purchasing)
  - [👨‍💻 Maintainer](#-maintainer)

## 📖 About

The **ZSWatch-Dock** project provides the hardware design and production files for a docking station tailored to the ZSWatch ecosystem.  
It is built with **KiCad** and integrates a full **CI/CD pipeline** using **KiBot**, ensuring reproducible outputs for documentation, manufacturing, and releases.

Key features:

- 🛠️ Open-source hardware design
- 📦 Automated generation of Gerber, BoM, and documentation via KiBot
- 🔄 Workflow stages (DRAFT → PRELIMINARY → CHECKED → RELEASED) for structured releases
- 📝 Clear documentation and changelog to track progress
- 🌍 Designed with collaboration and transparency in mind

![Complete](/production/dock-hw/Images/ZSWatch-Dock-angled_top.png)

Please check the [wiki](https://github.com/ZSWatch/ZSWatch/wiki) for more information about the project.

## 📂 Directory Breakdown

- **`.github`**: GitHub related files
- **`.gitignore`**: Ignored files list
- **`dock`**: KiCad project for the dock
- **`production/PCBWay`**: Manufacturing outputs (Gerbers, etc.) for PCBWay
- **`CHANGELOG.md`**: Version history
- **`LICENSE`**: Project license (GPL-3.0)
- **`README.md`**: Project overview

## Purchasing

TBD

## 👨‍💻 Maintainer

- [Daniel Kampert](mailto:danielkameprt@kampis-elektroecke.de)
- [Jakob Krantz](mailto:mail@jakobkrantz.se)
