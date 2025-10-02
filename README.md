# InstallForge Translations

## Overview
This repository is the official source for translations of InstallForge. Strictly speaking, these are translations for setup packages that can be created with InstallForge.
The translations are available in the form of plain-text files in UTF-8 with BOM encoding; files with the so-called ``.ifl`` extension (also referred to as _InstallForge Language File_).

> [!NOTE]
> All language files contained in the branch main represent the latest available versions and will be bundled with the next release of InstallForge.

## How to Install
If you would like to use specific language files contained in this repository, which may not be present in your local InstallForge installation, proceed with the following steps:
1. Clone this repository and make sure you are in branch main.
2. Move the specific language files of interest into the ``lang`` folder located inside the root installation directory of InstallForge [^1].
3. In case InstallForge is still running, restart the application.

[^1]: The absolute path is typically ``C:\Program Files (x86)\solicus\InstallForge\lang\``.

## How to Contribute

The language files contained in this repository are largely provided by people from the InstallForge user community.
If you would like to contribute and provide your language file for future releases of InstallForge, please feel free to do so through the _fork and pull request_ workflow.

---
Author: Soner Boztas
