# Awesome Windows on Linux (Only funny)

<p align="center"><img src="awologo.png" alt="Awesome Windows on Linux Logo" width="520"></p>

> A collection of projects that bring the Windows experience to Linux — from hardcore reverse engineering to hilarious pranks.

**en-US** | [zh-CN](README.zh-CN.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This list collects open-source projects that replicate, simulate, or parody the Windows ecosystem on Linux. Projects are grouped by **form** (CLI tools, GUI apps, system interaction, low-level/reverse engineering), and each carries an **intent tag** — `[Practical]` for things you can actually use, `[Prank]` for things you should not run on a production machine.

---

## Contents

- [Info](#info)
- [CLI Tools](#cli-tools)
- [GUI Applications](#gui-applications)
- [System Interaction](#system-interaction)
- [Low-level / Reverse Engineering](#low-level--reverse-engineering)

- **Docs**
  - [Contribute](#contribute)
  - [Create your own project entry](#create-your-own-project-entry)
  - [Troubleshooting](#troubleshooting)
  - [License](#license)

---

## Info

> I don't know what to put here either, haha.

### [Awesome Windows on Linux](https://github.com/windowix/awesome-windows-on-linux)

Intro: A curated collection of open-source projects that replicate, simulate, or parody the Windows ecosystem on Linux.

Restores: Curating and organizing projects that recreate Windows.

- License: MIT
- Authors: [windowix](https://github.com/windowix), [HelloAIXIAOJI](https://github.com/HelloAIXIAOJI)
- Primary language: en-US
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1mMgs6gET6

## CLI Tools

> Command-line tools that restore Windows terminal commands on Unix.

### [Linux-Autoplay](https://github.com/xusk1234/Linux-Autoplay) [Prank]

Intro: A USB drive notification fix experience for Linux users

Restores: AutoPlay (USB notification repair)

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV12c8y6LEXv/

### [PowerShell-For-Linux](https://github.com/SweetenedSuzuka/PowerShell-For-Linux) [Practical]

Intro: A PowerShell-style shell interpreter for Linux, implemented in pure Go with zero third-party dependencies, supporting both the 5.X and 7.X command sets.

Restores: The Windows PowerShell command-line experience: an object pipeline, 114 built-in cmdlets, and .ps1 scripting, letting you drive Linux with PowerShell-style commands.

- License: MIT
- Authors: [SweetenedSuzuka](https://github.com/SweetenedSuzuka)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: (pending)

### [WSL-for-Linux](https://github.com/xusk1234/WSL-for-Linux) [Prank]

Intro: A WSL-like experience for Linux users

Restores: Windows Subsystem for Linux (WSL)

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV1UN8q6bE82/

### [Winget-for-Linux](https://github.com/jihan-hanhan/Winget-for-Linux) [Prank]

Intro: A shell script wrapper that brings the Winget CLI experience to Linux.

Restores: Winget from App Installer (https://apps.microsoft.com/detail/9nblggh4nns1)

- License: MIT
- Authors: [jihan-hanhan](https://github.com/jihan-hanhan/)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1S1b96GEXb

### [aptx](https://github.com/WenAnrong/aptx)

Intro: An enhanced apt wrapper that recommends similar software after installing/removing packages.

Restores: The 'bundleware recommendations' nuisance experience when installing software.

- License: MIT
- Authors: [WenAnrong](https://github.com/WenAnrong)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1LNgG69EMe

### [cmd](https://github.com/ChenPi11/cmd) [Practical]

Intro: A faithful reimplementation of Windows `cmd.exe` written from scratch in pure C89, with zero POSIX dependencies, running on any Unix.

Restores: The Windows `cmd.exe` command interpreter (batch scripting, pipes/redirection, 40+ built-in commands).

- License: GPL-3.0
- Authors: [ChenPi11](https://github.com/ChenPi11)
- Primary language: en-US
- Supported languages: en-US / zh-CN / zh-MS / zh-WY
- Intro video: https://www.bilibili.com/video/BV1wkuH64EE8

### [Windowshit](https://github.com/HelloAIXIAOJI/windowshit) [Practical]

Intro: A collection of Windows command-line tools rewritten in Rust, running cross-platform.

Restores: 24 Windows command-line tools (ipconfig / ping / robocopy / systeminfo...).

- License: MIT
- Authors: [HelloAIXIAOJI](https://github.com/HelloAIXIAOJI)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1Pzuy6oEZm

## GUI Applications

> Graphical apps that recreate Windows desktop interfaces.

### [Devices Manager for Linux](https://github.com/xusk1234/Devices-Manager-for-Linux) [Prank]

Intro: A device manager for Linux

Restores: Device Manager

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1k2b16zEGe/

### [Lindows Troubleshooting](https://github.com/BobbyChengCN0518/Lindows-Troubleshooting) [Prank]

Intro: I fixed the bug that prevented using Troubleshooting on Linux and wasted time. Please be cautious when opening this program, as it will waste one precious minute of your life.

Restores: Troubleshooting

- License: MIT
- Authors: [BobbyChengCN0518](https://github.com/BobbyChengCN0518)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: (pending)

### [Lindows_Control](https://github.com/BobbyChengCN0518/Lindows_Control) [Prank]

Intro: I fixed the bug where the control panel couldn't be used on Linux. 
 The language can be configured via a JSON file, with zh and en being the default supported languages

Restores: Control

- License: MIT
- Authors: [BobbyChengCN0518](https://github.com/BobbyChengCN0518)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: (pending)

### [Linux-Auto-Fix](https://github.com/xusk1234/Linux-Auto-Fix) [Prank]

Intro: A handy auto-repair tool for Linux users

Restores: Startup Repair

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1G5b86jEbJ/

### [Linux-Sticky-key](https://github.com/xusk1234/Linux-Sticky-key) [Prank]

Intro: A sticky key experience for Linux users

Restores: Windows Sticky Keys

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1yebr6wEj4/

### [Linux-Store](https://github.com/xusk1234/Linux-Store) [Prank]

Intro: A Microsoft Store experience for Linux users

Restores: Windows Store

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV1Ei8n6PEe7/

### [LinuxDefender](https://github.com/xusk1234/LinuxDefender) [Prank]

Intro: A non-functional antivirus software for Linux

Restores: Windows Defender

- License: MIT
- Authors: [xusk1234](https://github.com/xusk1234)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1hrgs6mETH/

### [UMessageBox](https://github.com/0x8000S/UMessageBox) [Practical]

Intro: I fixed the bug where UWP pop-ups didn't show up on Linux

Restores: UWP pop-up on Windows 10

- License: MIT
- Authors: [0x8000S](https://github.com/0x8000S)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1QLbD6KEiU

### [WinSAT for *nix](https://github.com/WhatDamon/WinSAT)

Intro: A standalone software designed to provide a Windows-style system performance assessment and experience index.

Restores: Windows System Assessment Toolkit

- License: WTFPL
- Authors: [WhatDamon](https://github.com/WhatDamon)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1MegT68E15

### [Windows Search](https://github.com/WhatDamon/WindowsSearch) [Prank]

Intro: A standalone app that brings the poor search experience from Windows to the *nix world

Restores: Windows Taskbar Search and Indexing Features

- License: WTFPL
- Authors: [WhatDamon](https://github.com/WhatDamon)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1jruf6QEmh

### [WindowsWidget-for-Linux](https://github.com/phillin-liu/WindowsWidget-for-Linux)

Intro: A Linux desktop widget panel modeled after the Windows 11 Widgets board; it slides in from the right edge of the screen and integrates news, weather forecasts, and a date/clock display, while offering a graphical settings interface.

Restores: Windows Widget

- License: MIT License
- Authors: [phillin-liu](https://github.com/phillin-liu)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: (pending)

### [Animated-plasma-task](https://github.com/SkyShadowHero/Animated-plasma-task) [Practical]

Intro: Adds Windows-style animations and decorations to the Linux (KDE) taskbar.

Restores: The Windows taskbar animation experience (icon press scale, minimize bounce, window entry/exit animations, hover highlight and indicator bar).

- License: GPL-2.0
- Authors: [SkyShadowHero](https://github.com/SkyShadowHero)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: (pending)

### [Explorer-for-Linux](https://github.com/macOS-Terminal/Explorer-for-Linux) [Prank]

Intro: A desktop program that deeply replicates the Win11 file-management experience on Linux.

Restores: The Win11 File Explorer interface (including the classic 'Not Responding' experience).

- License: Unspecified
- Authors: [macOS-Terminal](https://github.com/macOS-Terminal)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1ZWgV68EtU

### [Explorer-for-Linux (xbodwf)](https://github.com/xbodwf/explorer-for-linux) [Practical]

Intro: A Windows 11 style file manager for Linux, built with Electron + Vue and WinUI-style web components.

Restores: The Win11 File Explorer experience (Fluent/WinUI look and feel).

- License: GPL-3.0
- Authors: [xbodwf](https://github.com/xbodwf)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: (pending)

### [linux-winver](https://github.com/DeepslateQAQ/linux-winver) [Prank]

Intro: I fixed the bug where Linux non-KDE desktop environments don't have winver.

Restores: winver

- License: GPL-3.0
- Authors: [DeepslateQAQ](https://github.com/DeepslateQAQ)
- Primary language: en-US
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV143b96iEKx/

### [mmclinux](https://gitee.com/windowsuninstaller/mmclinux) [Practical]

Intro: A cross-platform tool mimicking the Windows Management Console, built with tkinter.

Restores: The MMC console (MDI child windows, snap-ins, window embedding).

- License: MIT
- Authors: [WindowsUninstaller](https://gitee.com/windowsuninstaller)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV1gVuB6nEQk

### [NotepadOnLinux](https://github.com/linux-user-114514/NotepadOnLinux) [Practical]

Intro: A standalone program that recreates Windows Notepad on Linux.

Restores: The Windows Notepad interface.

- License: Unspecified
- Authors: [linux-user-114514](https://github.com/linux-user-114514)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1aigV6HETK

### [openconsole_linux](https://github.com/lanlan1o/openconsole_linux) [Practical]

Intro: A Linux port of Microsoft's Windows Terminal / OpenConsole terminal engine (~95% upstream code), hiding Windows API dependencies behind a lightweight compatibility layer, with a Qt6 terminal-grid frontend.

Restores: Restores conhost.

- License: MIT
- Authors: [lanlan1o](https://github.com/lanlan1o)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1opbS6rE2g

### [regedit](https://github.com/heyManNice/regedit) [Practical]

Intro: A system configuration file browser that maps `/etc`, `~/.config`, and `/boot` to a registry tree and auto-detects multiple config formats.

Restores: The registry editor interface (left tree + right key/value list).

- License: GPL-3.0 (declared in README; no LICENSE file shipped)
- Authors: [heyManNice](https://github.com/heyManNice)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1CWuV6iEW6

### [runbox](https://github.com/HelloAIXIAOJI/runbox) [Practical]

Intro: A run dialog on Linux that pops up with `Super+R`, with an Adwaita look following the system theme.

Restores: The Win+R 'Run' dialog.

- License: MIT
- Authors: [HelloAIXIAOJI](https://github.com/HelloAIXIAOJI)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1CxgJ6pEHr

### [SAS-for-Linux](https://github.com/macOS-Terminal/SAS-for-Linux)

Intro: A Windows 11-style Ctrl+Alt+Delete secure attention screen implemented in C++/Qt 6, supporting X11 and Wayland (GNOME/KDE/Sway/Hyprland/Niri).

Restores: The Windows 11 secure attention screen (lock / switch user / log out / change password / task manager + network / accessibility / power).

- License: Unspecified
- Authors: [macOS-Terminal](https://github.com/macOS-Terminal)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1FQgn6sERt

### [taskschd4Linux](https://github.com/1ctrl-cv/taskschd4Linux) [Practical]

Intro: A Windows Task Scheduler implemented in Python, featuring an MMC-style interface layout and supporting cron and systemd timers.

Restores: Windows Task Scheduler, Most of the UI and behavior

- License: LGPL-2.1
- Authors: [B84F2246](https://github.com/1ctrl-cv)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV18UbY6SE7f/

## System Interaction

> Projects that hook into system services: PAM modules, popups, global hotkeys.

### [Linux-Activator](https://github.com/jihan-hanhan/Linux-Activator)

Intro: Restored the 'Activate Windows' window (without watermark; installing activate-linux is recommended), and opened up the configuration file and interface to add more restrictions to 'unactivated Linux'.

Restores: Restores the 'Activate Windows' window (without watermark)

- License: MIT
- Authors: [jihan_hanhan](https://github.com/jihan-hanhan)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV1cj8c6jE7f

### [adpop](https://github.com/MEKCCK/adpop) [Prank]

Intro: A general-purpose ad-popup service rendered fully from scratch, callable by other software.

Restores: Windows-style malicious ad popups (animated images / video / audio / popup spam / non-closable).

- License: Unspecified
- Authors: [MEKCCK](https://github.com/MEKCCK)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1ARgV6gEGm

### [libobscure](https://github.com/LyCecilion/libobscure) [Prank]

Intro: Replace the error messages with Windows-style error codes.

Restores: Windows-style error codes.

- License: MIT
- Authors: [Limity'roChen](https://github.com/LyCecilion)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV1QVgc6UEcw/

### [libschrodinger](https://github.com/LyCecilion/libschrodinger)

Intro: Pops up an "application error" dialog when a program encounters a fatal error.

Restores: The "application error" dialog.

- License: MIT
- Authors: [Limity'roChen](https://github.com/LyCecilion)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: https://www.bilibili.com/video/BV1Qag36jETo/

### [Linux_uac](https://github.com/WenAnrong/Linux_uac) [Prank]

Intro: Recreates Windows UAC (User Account Control) on Linux via a custom PAM module: the screen dims and freezes, then a password prompt appears when you run sudo.

Restores: The Windows UAC dialog (dim & freeze + password check + Yes/No + chime).

- License: MIT
- Authors: [WenAnrong](https://github.com/WenAnrong)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV1qjgn6EErZ

## Low-level / Reverse Engineering

> Binary-format and kernel-adjacent projects: DRM rendering, PE/ELF, system internals.

### [bsod](https://github.com/heyManNice/bsod) [Prank]

Intro: A blue-screen demo tool that renders directly on the Linux physical display, grabbing DRM Master, with multi-language and log monitoring.

Restores: The Win10 Blue Screen of Death interface (with QR code).

- License: MIT
- Authors: [heyManNice](https://github.com/heyManNice)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN / zh-TW / ja / ko
- Intro video: https://www.bilibili.com/video/BV1xcuU6uEyw

### [LinuxForWindows](https://github.com/dyz131005/LinuxForWindows)

Intro: A binary conversion tool that offline-converts Windows PE executables into Linux ELF at the file-format level.

Restores: PE / ELF file format structures (header, section table, program headers, dynamic segment).

- License: MIT
- Authors: [dyz131005](https://github.com/dyz131005)
- Primary language: zh-CN
- Supported languages: zh-CN
- Intro video: https://www.bilibili.com/video/BV1p1gE6DEVF

### [LSW](https://github.com/LING71671/lsw) [Practical]

Intro: A production-grade Linux Subsystem for Windows written in pure Rust, providing 100% architectural and operational parity with Microsoft WSL. Official website & playground: https://lsw.int0.cc

Restores: WSL1/WSL2/WSLg ecosystem on Linux (kernel-level PE execution, lswpath path translation, LSWENV cross-environment pipeline, ConPTY bridge, Smart Dual-Engine Auto-Routing).

- License: MIT
- Authors: [LING71671](https://github.com/LING71671)
- Primary language: zh-CN
- Supported languages: zh-CN / en-US
- Intro video: (pending)

### [windows_update_in_linux](https://github.com/WenAnrong/windows_update_in_linux) [Prank]

Intro: A prank program showing a fake Windows update screen: 50% chance of a real update+reboot, 50% chance of a blue screen.

Restores: The Windows update screen (success progress / failure blue screen).

- License: MIT
- Authors: [WenAnrong](https://github.com/WenAnrong)
- Primary language: zh-CN
- Supported languages: en-US / zh-CN
- Intro video: https://www.bilibili.com/video/BV15iuR6zEBE

---

## Contribute

Welcome to submit PRs to add more "Windows on Linux" projects. Each entry should include: project link, license, authors, primary/supported languages, a one-line intro, and what Windows part it restores.

### Create your own project entry

Run `python main.py new`, pick a group, and enter a project name when prompted. The script creates the project directory (it prints the generated path) with one JSON file per language.

Generated directory structure:

```text
my-awesome-tool/
├── zh-CN.json
└── en-US.json
```

Open the project JSON and fill in the fields:

```json
{
  "name": "my-awesome-tool",
  "intro": "",
  "restores": "",
  "license": "",
  "url": "",
  "authors": [],
  "lang_primary": "zh-CN",
  "lang_supported": ["zh-CN"],
  "intent": "practical"
}
```

| Field | Required | Description |
| --- | --- | --- |
| `name` | yes | Project display name |
| `url` | yes | Repository URL |
| `intro` | yes | One-line intro |
| `restores` | yes | Which Windows part it restores |
| `license` | yes | Open-source license |
| `authors` | yes | List of authors, each with `name` and `url` |
| `lang_primary` | yes | Primary language |
| `lang_supported` | yes | Array of supported languages |
| `video` | no | Intro video link |
| `intent` | yes | Intent tag: `practical` / `prank` / `mixed` |

`intent` is orthogonal to the form-based group: **practical** = usable/safe, **prank** = parody/not for production, **mixed** = both.

After editing, regenerate and validate:

```bash
python main.py generate
python main.py lint
```

Then commit and open a Pull Request:

```bash
git add .
git commit -m "feat: add my-awesome-tool"
git push
```

Create the Pull Request; it merges once all Actions pass.

### Troubleshooting

- **`lint` fails**: run `python main.py check` and `python main.py cl` to locate the issue.
- **Language asymmetry**: each project must have a JSON file for every language present in `project-meta/`.
- **Removing an entry**: delete the project directory, then re-run `generate`.

---

## License

[MIT](LICENSE) © 2026 windowix


*Generated at: 2026-08-23 00:41 UTC*
