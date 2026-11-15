---
already_read: true
link: https://cleanyour.tv/
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Development_tool
type: Content
upload_date: '2026-11-15'
---

https://cleanyour.tv/

## Summary

CleanYourTV is an open-source tool to remove ads and bloatware from Android TV/Google TV devices, replacing the launcher with a clean, Apple TV-style interface—no root required, fully reversible.

**Overview**
- 58.1k+ GitHub stars, 7.5k+ forks, 440+ contributors.
- Works on Android TV/Google TV (Sony, Philips, TCL, Xiaomi, Nvidia Shield, etc.), not Samsung Tizen, LG webOS, or Fire TV.
- One command undoes all changes; nothing is uninstalled.

**Setup**
- Enable Wi-Fi debugging on TV, run a script from a computer on the same network.
- Supports Wireless ADB for newer Google TV sets.
- Backup includes package lists, settings, and a restore script.

**Debloat**
- Disables manufacturer telemetry, ads, and unnecessary background services via `pm disable-user`.
- Avoids disabling critical system packages (e.g., `com.android.*`, TV middleware).
- Optional: Ad-blocking DNS (Private DNS mode, excludes YouTube ads).

**Launcher**
- Installs a lightweight, customizable Apple TV-style launcher (dock + grid, black theme).
- Supports 4–7 dock slots, deterministic D-pad navigation.
- Compatible with Android 8.0+ (SDK 26+); checks for APK signature restrictions.

**Verification**
- Screenshots and `dumpsys` checks confirm changes.
- Restore script provided; all steps reversible.

**Non-Android TVs**
- Separate guide for Samsung/LG/Roku to disable tracking via remote settings.

## Links

- [CleanYourTV GitHub Repository](https://github.com/Gathin23/cleanyourtv) : The official GitHub repository for CleanYourTV, containing the source code, installation prompts, troubleshooting guides, and documentation for removing ads and bloatware from Android TV/Google TV devices.
- [CleanYourTV PROMPT.md](https://github.com/Gathin23/cleanyourtv/blob/main/PROMPT.md) : A detailed guide and prompt for setting up CleanYourTV using AI coding assistants like Claude Code. Includes step-by-step instructions for debloating Android TV/Google TV devices and replacing the launcher with a clean interface.
- [CleanYourTV Buy Me a Coffee](https://buymeacoffee.com/gathint) : A donation page for CleanYourTV, allowing users to support the project financially. This is relevant as it provides a way to contribute to the open-source tool mentioned in the content.
- [Trendshift CleanYourTV Repository Stats](https://trendshift.io/repositories/310225) : A page showcasing statistics and metrics for the CleanYourTV GitHub repository, including stars, forks, contributors, and press coverage. Useful for tracking the project's popularity and impact.


## Topics

![[topics/Tool/ADB]]

![[topics/Library/adb shell]]

![[topics/Platform/Android TV]]

![[topics/Platform/Google TV]]

![[topics/Tool/CleanYourTV]]

![[topics/Concept/Debloating]]

![[topics/Concept/Launcher replacement]]

![[topics/Tool/pm]]

![[topics/Concept/ADB over Wi Fi]]

![[topics/Tool/dumpsys]]