# EnCase-Agent-Uninstaller-macOS-Catalina

This is a signed, notarized uninstaller PKG file for the EnCase Enterprise/Direct agent installed on macOS 10.15 (Catalina). A version tested for macOS 14 (Sonoma) is to be found in the following repository:

- https://github.com/sdckey/EnCase-Agent-Uninstaller-macOS-Sonoma

Provided that macOS has been instructed to allow apps from the App Store and identified developers (a setting on the Security & Privacy preferences page), the PKG file should open without warning.

It is not an official OpenText product and consists solely of a `postinstall` BASH script, which is rudimentary in nature.

The script performs no validation nor will it report anything other than a successful execution.

This software is released under the terms of the [Apache Licence Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

The PKG file can be downloaded from the [Releases](https://github.com/sdckey/EnCase-Agent-Uninstaller-macOS-Catalina/releases) page.
