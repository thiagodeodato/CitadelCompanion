# The Citadel of Chaos - Adventure Companion & Chronicle

A lightweight, single-file, vibe-coded companion app designed for the classic Fighting Fantasy gamebook *The Citadel of Chaos* (written by Steve Jackson).

Built to replace worn-out pencil-and-paper character sheets, this tool tracks your hero's attributes, manages the book's unique spell allocation system, logs manual combat encounters, and chronicles every paragraph decision across multiple playthroughs to help you chart the "True Path" to Balthus Dire.

---

## About The Project

*The Citadel of Chaos* is renowned for its labyrinthine structure, lethal dead-ends, and spell-selection mechanics. Winning requires mapping previous attempts, remembering vital paragraph references, and conserving spell charges.

This project is a 100% client-side, zero-dependency **single HTML file** running Vanilla JavaScript and Tailwind CSS. It requires no backend, works offline directly from any mobile or desktop browser (`file:///...`), and keeps all data locally on your device.

---

## Key Features

### Character Creation & Spell Grimoire

* **Authentic Formulas:** Roll or input initial stats: **SKILL** ($1D6 + 6$), **STAMINA** ($2D6 + 12$), **LUCK** ($1D6 + 6$), and **MAGIC** ($2D6 + 6$).
* **Dynamic Spell Allocation:** Spend your Magic points across all 12 spells (*Creature Copy / Duplicate Creature, E.S.P., Fire, Illusion, Levitation, Luck, Shielding, Skill, Stamina, Weakness, Strength, and Foolery*).
* **Spell Consumption & Recovery:** Track remaining spell charges during gameplay with visual indicators and a safe reset mechanism for story-driven restoration items.

### Manual Combat Engine & Action Log

* **Collapsible Monster Panel:** Keep monster stats visible without cluttering your mobile screen.
* **Animated Dice Roller:** Roll 1D6 or 2D6 with an interactive rolling animation and automatic sum logging for easy mental math.
* **Debounced Event Logging:** High-frequency stat tweaks consolidate into clean, timestamped event logs to prevent clutter.

### Multi-Adventure Journal & Cross-Timeline Search

* **Decision Tracking:** Log paragraph numbers ($\S$) and decision notes with timestamps and dates (`DD-MM-YY`).
* **Live In-Journal Editing:** Fix typos or delete accidental entries directly on your active character sheet.
* **Global Chronicles (Archive):** View and expand collapsible logs across all past attempts.
* **Smart Filter & UPPERCASE Scanner:** Search notes by text, paragraph number, or isolate crucial hints written in ALL CAPS.

### Local Backup & Campaign Portability

* **Multi-Campaign Database:** Switch seamlessly between active and past adventurers via the horizontal character carousel.
* **Offline JSON Export/Import:** Download timestamped backups (`backupcidadela-YYYY-MM-DD-HH-MM-SS.json`) straight to your device to prevent data loss on browser cache purges.
* **Retrocompatible Engine:** Ingests and sanitizes both legacy single-sheet saves and modern multi-campaign files.

---

## Getting Started
* Use it Online: https://thiagodeodato.github.io/CitadelCompanion/
* Or Download it!
1. Download or save `index.html` to your phone or computer.
2. Open the file in any modern web browser (Google Chrome, Safari, Firefox).
3. Roll your attributes, choose your spells, and enter the gates of the Citadel!
