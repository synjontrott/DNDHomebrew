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
- **Technical Rules & RAW Audit (August 2026):** Fixed missing durations (Warrion `Elemental Trance` 1-min duration), missing action costs (Animal Spirit, Bonded Weapon, Automaton Assistant), and RAW loopholes (Violent Soldier, Smithy discount reselling).
- **6-Agent 2024 OP Balance Sweep (August 2026):** Multi-agent sweep adjusted Techno Railgun (2d10 Loading), capped spell damage multipliers (Fusion Blast, Potent Spellcasting), re-leveled tier-inappropriate features (Mind Break, Rift Maker), and set Epic Boon prerequisites to Level 19+.
- **Species Traits & Benchmarks (August 2026):** Genempriea updated to 35ft base speed + *Overclocked Actuators* (Bonus Action Dash PB/LR). Plunesako expanded to grant dual skills (Origin Feat removed for balance parity). Krenpowen/Tenebrie rebuilt as the standard elementally charged species (2024 Human equivalent) with dual skill proficiencies and *Resourceful Determination* (Heroic Inspiration on Long Rest) — *Elemental Heritage* Origin Feat removed to achieve exact 2024 Human benchmark parity.


- **Per-Region Magic Item Compendiums (August 2026):** 150 total magic items added to Chapter 4 across 5 regional compendiums (Ninjonia, Techno, Warrion, Nidosis, Shadow/Ancient Elsaither).
- **High-Fantasy Subclass Titles & Disconnect Fixes (August 2026):** High-fantasy titles applied to all subclasses and feature disconnects resolved.
- **Glass Cannon Mutation Audit (August 2026):** All 21 mutations tuned to strict high risk / high reward glass cannon paradigms.
- **Full 28-Deity Spell Compendium (August 2026):** Chapter 6 standardized to 100% compliance across all 28 Deities starting with Pireous down to Zarta (168 total spells), providing a 3-option cantrip `(Utility), (Utility), (Damage)` + 5 unique spells mapped to 2nd, 3rd, 4th, 5th, and Capstone tiers.
- **Inherent Magic & 2024 Class Parity Audit (August 2026):** Standardized *Elementally Charged* across all 5 species to grant Primary Resistance + 1 Elemental Cantrip of choice, ensuring 100% balance and zero exploits when played with standard D&D 2024 PHB classes.
- **Campaign Guide Modularization (August 2026):** Split the monolithic `Legends_of_the_Elsaither_Campaign_Guide.md` into 7 chapter files in the `Chapters/` directory for efficient agent-based editing and reduced token overhead per task.
- **Beast Master Class Added (August 2026):** New Wisdom-based half-caster added as `Chapters/Chapter_02c_Beast_Master.md`. Key mechanics: 1d8 HD, Primal Essence (PE) pool, three pillars (Spirit Companion, Aspect Mutations, Wildshape), Deity Blessing at L1 (element-match restriction), Weapon Mastery (2), Extra Attack (L5), Enhanced Pillars (L11), Primal Arcanum — PB/LR free cast of a 4th/5th-level spell (L13 & L17), PHB Epic Boon feat (L19), Avatar of the Mark capstone (L20). Six Marks of the Wild: **Wolf**, **Dragon**, **Bear**, **Owl**, **Eagle**, **Sheep**.
- **8-Chapter Comprehensive 2024 Balance Sweep (August 2026):** 8-agent parallel audit resolved 37 critical and 34 minor D&D 2024 compliance issues. Key fixes: *Elementally Charged* stripped to Resistance + Cantrip only; Primal Arcanum corrected to 4th/5th-level spells; all 28 deity damage cantrips now scale at 5th/11th/17th level; 7 deity spells rebalanced from 9th-level effects; Gruhunsh Haste corrected to 1 minute; Railgun to 1d12; Blood/Black Bone Dangers now harm the caster; Warrion Trance spell-lock added; Techno attunement corrected to L10/L14; Ink-Web limited to 1/LR.
- **Cantrip Standardization:** All cantrips provide utility or temporary benefits rather than permanent healing or overpowered debuffs.
- **Currency:** Standardized as "cc" (Crystalarium Currency) across all primary documents.
- **Reference Management:** Legacy homebrew volumes and individual class files are archived in the `ReferenceDocuments/` directory.

## Key Files
| File | Purpose |
|---|---|
| [`Chapters/`](./Chapters/) | Modular chapter files — **source of truth** for all edits |
| [`Legends_of_the_Elsaither_Campaign_Guide.md`](./Legends_of_the_Elsaither_Campaign_Guide.md) | Auto-generated monolith (all chapters concatenated) — use this for PDF/Docs export |
| [`Mutations_Expansion_Guide.md`](./Mutations_Expansion_Guide.md) | 21 elemental mutation rules |
| [`ReferenceDocuments/`](./ReferenceDocuments/) | Archived legacy volumes |
