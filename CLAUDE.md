# D&D Homebrew: Legends of the Elsaither (LotE) — Claude Guide

> **Cross-Reference:** This file works alongside [`GEMINI.md`](./GEMINI.md) and [`AGENTS.md`](./AGENTS.md). All three files share the same project mandates; refer to them together for full context.

## Project Objective
Create a perfectly balanced D&D Homebrew guidebook based on LotE Lore. The result should be fun to play and complement the standard D&D 2024 classes as if it were a canon rulebook.

## Core Mandates
- **2024 Compatibility:** All content must be built for and balanced against the D&D 2024 rules (PHB, DMG, MM).
- **Balance:** Prioritize mathematical fairness and progression consistency. Ensure homebrew options do not overshadow or underperform compared to official options.
- **Lore Fidelity:** All descriptions, names, and mechanics must align with the "Legends of the Elsaither" campaign setting.
- **Technical Writing:** Use the standard wording and syntax found in official D&D sourcebooks (e.g., proper capitalization of game terms, clear action economy).

## Subagent Roles (see [`AGENTS.md`](./AGENTS.md) for full definitions)
- **balance_expert** — Mathematical balance audits, comparison to 2024 PHB/DMG standards.
- **lore_keeper** — LotE world-building consistency, elemental systems, 'cc' currency.
- **rules_editor** — D&D 2024 technical writing style, action economy clarity.

## Project Status & Guidance (August 2026)
- **Feats Architecture:** Comprehensive feats established — Origin, General (Level 4+), Mastery (Level 12+), and Epic Boons (Level 16+), all scaled to D&D 2024 standards.
- **Mutations Expansion:** 21 rare elemental mutations formalized in `Mutations_Expansion_Guide.md`. All use dynamic scaling (Spell Save DC, PB, Spellcasting Modifier).
- **High-Risk/High-Reward System:** Every mutation follows a strict Power/Danger framework. Dangers use D&D 2024 mechanics (Hit Dice, scaled Saving Throws, self-damage).
- **Damage Profiles:** All mutations follow a 1-primary/3-secondary damage type profile.
- **White Shadow Fix (August 2026):** The White Shadow mutation's power was revised. The redundant "no penalties in bright light" clause was replaced with a meaningful stealth/distraction utility — a Dexterity (Sleight of Hand) advantage and a short-rest blinding flash. The Danger was unchanged.
- **Deity Spell Integration (August 2026):** A "Deity Blessing" system was added to the Savaroen and Shadow Warrior classes, formalizing how characters with a chosen Deity gain access to their Deity Cantrip and Unique Spells. The deity spell descriptions in Chapter 6 were expanded to full D&D 2024 formatting.
- **Cantrip Standardization:** All cantrips provide utility or temporary benefits rather than permanent healing or overpowered debuffs.
- **Currency:** Standardized as "cc" (Crystalarium Currency) across all primary documents.
- **Reference Management:** Legacy homebrew volumes and individual class files are archived in the `ReferenceDocuments/` directory.

## Key Files
| File | Purpose |
|---|---|
| [`Legends_of_the_Elsaither_Campaign_Guide.md`](./Legends_of_the_Elsaither_Campaign_Guide.md) | Primary rulebook: races, classes, feats, equipment, spells, deities |
| [`Mutations_Expansion_Guide.md`](./Mutations_Expansion_Guide.md) | 21 elemental mutation rules |
| [`Homebrew_Balance_Report.md`](./Homebrew_Balance_Report.md) | Balance audit log |
| [`ReferenceDocuments/`](./ReferenceDocuments/) | Archived legacy volumes |
