<div align="center">

# 🏢 Software Inc. | Persian Localization (پارسی‌ساز سافت‌ور اینک)
### *Official ParsiSaz Community Translation & Business Simulation Language Pack*

<br/>

[![ParsiSaz Portal](https://img.shields.io/badge/🌐_Documentation_Portal-parsisaz.github.io%2Fparsisaz-00f2fe?style=for-the-badge&logo=googlechrome)](https://parsisaz.github.io/parsisaz/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![Locale](https://img.shields.io/badge/Locale-fa__IR-emerald?style=for-the-badge)](#-project-structure)
[![Maintainer](https://img.shields.io/badge/Maintained_by-Danial_Pahlavan-blue?style=for-the-badge&logo=github)](https://github.com/DanialPahlavan)

</div>

---

## 📖 Overview
This repository contains the Persian localization mod for **Software Inc.** (by Coredumping), organized in accordance with the **ParsiSaz 2026 Game Localization Architecture (L10N-STD-2026)**.

---

## 🗂️ Project Structure (L10N-STD-2026)

```
Software-Inc-Game---Persian/
├── loc/                           # Decoupled Core Localization Data
│   ├── fa-IR/                     # Standard Persian .tyd & .xml definitions
│   │   ├── UI.xml / UI.tyd        # User interface & management panels
│   │   ├── Software.tyd           # Software product types & tech features
│   │   ├── Furniture.tyd          # Office items & servers
│   │   ├── Traits.tyd             # Employee personalities & skills
│   │   └── Tutorial.xml           # Interactive onboarding guide
│   └── glossaries/                # Business & software industry terminology
├── game_assets/                   # Game Engine Drop-in Directory
│   └── Translations/Persian/      # Drop-in folder for Software Inc.
├── HISTORY.md                     # Semantic Versioning Changelog
├── README.md                      # Project documentation
└── LICENSE                        # GNU General Public License v3
```

---

## 🚀 Installation Instructions

1. Download or clone this repository.
2. Copy the `game_assets/Translations/Persian` folder into your game's translation directory:
   ```text
   <Software_Inc_Directory>/Translations/Persian/
   ```
3. Open Software Inc., navigate to **Options > Localization**, and select **Persian** from the language menu.
4. Enjoy building your software empire entirely in Persian!

---

## 🌐 Central Documentation & Bug Reports
For more details on engine hurdles, reverse engineering, and other games in the ecosystem:
👉 **[Open ParsiSaz Live Portal](https://parsisaz.github.io/parsisaz/)**
