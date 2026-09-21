![preview](https://raw.githubusercontent.com/agencyfelan-cell/CraftTheWorld-Save-Smith/main/thumb_b48b.svg)
[![Download](https://raw.githubusercontent.com/agencyfelan-cell/CraftTheWorld-Save-Smith/main/btn_fa7414c.svg)](https://agencyfelan-cell.github.io/CraftTheWorld-Save-Smith/)

# 🧰 NAME: CraftWorldModifier

**A Windows desktop modifier for Craft The World — local-only operation, save backups, and Steam support.**

---

## 📜 Overview

CraftWorldModifier is a lightweight, Windows-native desktop companion designed for players who want to sculpt their Craft The World experience without ever touching a server or exposing their data to the internet. Think of it as a quiet workshop behind the scenes of your favorite sandbox fortress — a place where you can rearrange resources, fine-tune dwarven inventories, protect your progress with automatic backups, and still keep everything neatly tied into Steam.

This project lives entirely on your own machine. No cloud sync, no remote telemetry, no third-party relays. What happens in your save folder stays in your save folder.

---

## ✨ Why This Exists

Craft The World is a delightful blend of strategy, survival, and base-building — but sometimes the grind isn't the fun part. Sometimes you want to experiment with building layouts, rearrange a stockpile of ore, or recover from a disastrous cave collapse without starting fresh. CraftWorldModifier was born from that exact moment: the moment you wish you had a gentle nudge rather than a full reset.

Instead of invasive changes, this tool offers a careful, backup-first approach to modifying local save data — respecting your world, your time, and your Steam library.

---

## 🎯 Core Feature Set

- 🖥️ **Windows-First Desktop Interface** — Built natively for Windows 10 and 11, using system-native file dialogs and tray integration.
- 🔒 **Local-Only Operation** — No outbound network calls are made during editing, ensuring your save data never leaves your machine.
- 💾 **Automatic Save Backups** — Each modification creates a timestamped backup before any write occurs, so an undo is always one click away.
- 🎮 **Steam Library Awareness** — Detects common Steam installation paths and user profile folders to locate saves automatically.
- 🧭 **Save Slot Browser** — View and organize multiple worlds in one place with readable metadata like last-played date and world name.
- 🛠️ **Resource & Inventory Adjustments** — Modify item counts, tools, and stockpiles via a guided, non-destructive editor.
- 🧱 **World Tile Inspection** — Peek at tile data for terrain and constructions to plan large builds more confidently.
- 🌍 **Multilingual Support** — Interface strings available in multiple languages, with community-contributed translation files.
- ♿ **Responsive, Accessible UI** — Smooth scaling on high-DPI displays and keyboard-navigable layouts.
- 🔁 **Rollback Utility** — Restore any previous backup from a clean chronological list.
- 🧩 **Modular Plugin Hooks** — Extend the editor with your own scripts via a documented local plugin API.
- 🕒 **24/7 Community Support Presence** — Issues, discussions, and community-driven guides remain available around the clock.

---

## 🚀 Getting Started (Conceptual Flow)

This README avoids command-line choreography on purpose. Instead, picture the flow:

1. Launch the CraftWorldModifier desktop application on your Windows machine.
2. Point it at your Craft The World save directory — or let it auto-discover the usual Steam profile location.
3. Choose a world from your save slot browser.
4. Review the automatic backup prompt and confirm.
5. Make your adjustments through the guided editor.
6. Save and launch the game to see your changes reflected.

That's the whole journey. No install scripts to memorize, no environment variables to fiddle with.

---

## 🧠 Design Philosophy

CraftWorldModifier treats your save files the way a good archivist treats manuscripts: with gloves on, a camera rolling, and a copy stored in the vault before anything is written. Every feature is built around the principle that **your world is yours**, and the tool is only ever a lens — never a leash.

The second principle is transparency. There is no hidden network layer, no anonymous analytics ping, and no "phone home" check when you open the app. It is a sealed workshop.

The third principle is **graceful reversibility**. Any change can be undone. Any backup can be restored. Any mistake is a footnote, not a tragedy.

---

## 🧬 Multilingual Support

The interface ships with translation packs for a growing set of languages. The project embraces community contributions through simple JSON-based language files, so adding a new locale is as approachable as editing a text document.

Supported (or in progress) languages include:

- English
- 简体中文 (Simplified Chinese)
- 繁體中文 (Traditional Chinese)
- Deutsch
- Français
- Español
- Русский
- 日本語
- 한국어
- Polski

If your language isn't listed yet, the contribution guide explains how to add it without needing to touch the compiled code.

---

## 🖼️ Responsive UI & Visual Language

CraftWorldModifier adopts a compact, panel-driven interface that scales cleanly from 1080p laptops to ultrawide desktops. The layout prioritizes:

- Clear primary actions (Backup, Edit, Restore)
- Contextual side panels for resource and world data
- A dark, low-glare palette that plays nicely with long building sessions
- Tooltip-driven discovery so users aren't buried in documentation

The aesthetic leans toward a "workshop ledger" — parchment tones, ink-dark panels, and restrained accents.

---

## 🛡️ Safety, Privacy, and Local Operation

- **No outbound connections** are established during a modification session.
- **Steam integration** reads local files only; it does not authenticate on your behalf.
- **Backups** are written to a sibling directory so a failed operation never overwrites the original.
- **Logs** are stored locally and contain no personally identifying information.
- **No telemetry.** No account system. No remote configuration.

For users with heightened privacy needs, the app can be run from a portable folder with no registry footprint.

---

## 🧩 Extending the Modifier

A documented plugin API allows technically inclined users to write their own local transformation scripts. Plugins can:

- Register new editor panels
- Add custom validation rules for save integrity
- Provide import/export bridges for external formats
- Automate repetitive adjustments via scheduled local tasks

Plugins run in the same local sandbox as the core application and never gain network privileges.

---

## 🧪 Stability & Compatibility Notes

CraftWorldModifier is tested against current Craft The World releases on Steam. Because the game sometimes updates its save schema, the project maintains a compatibility checklist for each supported game version. When a mismatch is detected, the app refuses to write and suggests restoring from a backup — a deliberate, protective pause.

Older save formats may still be readable in review-only mode, meaning you can explore the data without committing changes.

---

## 🌐 SEO-Friendly Context

For players searching for a **Craft The World save editor**, a **Windows desktop modifier for Craft The World**, or a **local save backup utility for sandbox strategy games**, this repository aims to be a clear, honest destination. Keywords like *save backup*, *Steam support*, *local-only desktop tool*, and *multilingual interface* describe the project accurately — no exaggeration, no inflated promises.

If you arrived here looking for a way to **manage your Craft The World saves safely on Windows**, you're in the right place.

---

## 🗺️ Roadmap

- [x] Initial save browser
- [x] Automatic timestamped backups
- [x] Steam profile discovery
- [x] Multilingual framework
- [ ] Expanded tile inspection tools
- [ ] Portable mode documentation
- [ ] Community translation portal
- [ ] Advanced rollback timeline viewer
- [ ] Plugin marketplace (local, offline-indexed)
- [ ] Accessibility audit and improvements

---

## 🤝 Contributing

Contributions are warmly welcomed — from typo fixes to new translation files to plugin examples. The contribution guide emphasizes:

1. **Respect the local-only principle.** No feature may introduce mandatory network access.
2. **Backups are sacred.** Any new write path must first snapshot the original.
3. **Keep the UI approachable.** Clarity over cleverness.
4. **Document your changes.** Future maintainers are part of the audience.

---

## ❓ Frequently Asked Questions

**Is this safe to use with my Steam achievements?**
Yes. CraftWorldModifier edits local save files and does not interact with Steam achievement tracking.

**Will this work on macOS or Linux?**
The project targets Windows natively. Compatibility layers may work but are not officially supported.

**Do I need an internet connection?**
No. Once the application is on your machine, it operates entirely offline.

**Can I undo a change?**
Yes. Every modification creates a backup, and the rollback utility restores any of them.

**Does it support multiple languages?**
Yes. The interface ships with multilingual support and a community translation pipeline.

---

## ⚠️ Disclaimer

CraftWorldModifier is an independent, community-driven utility and is not affiliated with, endorsed by, or sponsored by the developers or publishers of Craft The World. All trademarks belong to their respective owners. Use of this tool is at your own discretion; always retain your own backups. The maintainers are not responsible for data loss resulting from misuse, incompatible game versions, or third-party plugins.

---

## 📄 License

This project is released under the **MIT License**. See the [LICENSE](./LICENSE) file for full details.

Copyright (c) 2026 CraftWorldModifier Contributors.

---

## 💬 Support

Community discussions, bug reports, and feature requests are handled through repository issues and discussion threads. Support is available around the clock thanks to contributors across multiple time zones — 24/7 community presence, one message away.

---

[![Download](https://raw.githubusercontent.com/agencyfelan-cell/CraftTheWorld-Save-Smith/main/btn_fa7414c.svg)](https://agencyfelan-cell.github.io/CraftTheWorld-Save-Smith/)