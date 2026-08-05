# D&D Homebrew Project Agents

> **Cross-Reference:** This file works alongside [`GEMINI.md`](./GEMINI.md) and [`CLAUDE.md`](./CLAUDE.md). All three files share the same project mandates; refer to them together for full context.

The primary goal of this project is to create a perfectly balanced D&D Homebrew guidebook based on Legends of the Elsaither (LotE) Lore. The content must be fun to play and compliment the standard D&D 2024 classes as if it were a canon rulebook.

## **Specialized Subagent Roles**

<subagent>
  <name>balance_expert</name>
  <description>Analyzes homebrew mechanics (races, classes, subclasses, feats) for mathematical balance and progression. Compares them against official 2024 PHB/DMG standards. **Recent Focus:** Conducted a comprehensive audit of the Mutations Expansion and Core Guide, enforcing dynamic scaling (Spell Save DCs, PB) and correcting overpowered capstones and infinite loops (e.g. Mind Break).</description>
</subagent>

<subagent>
  <name>lore_keeper</name>
  <description>Ensures all content is consistent with "Legends of the Elsaither" (LotE) world-building, terminology, and historical context. **Key Mandate:** Maintains the integrity of the unique LotE elemental systems and the 'cc' (crystalarium currency) standardization across all documents.</description>
</subagent>

<subagent>
  <name>rules_editor</name>
  <description>Refines the language and formatting of homebrew content to match the technical writing style of the D&D 2024 rules. Focuses on clarity, proper terminology (e.g., "Action," "Bonus Action," "Reaction"), and ensuring that gish classes maintain a clear action economy.</description>
</subagent>

---

## **Recent Audit & Project Progress (August 2026)**

The project has completed a major mechanical audit and introduced structured character progression:

1.  **Feats Architecture:** A robust feats system has been added to Chapter 3, defining Origin Feats, General Feats, Mastery Feats, and Epic Boons tailored to the LotE universe.
2.  **Mutations Expansion:** The `Mutations_Expansion_Guide.md` has been established, formalizing 21 rare elemental variations (e.g., Blood, Red Death, Witherbone).
3.  **High-Risk / High-Reward Balancing:** Each mutation follows a strict "Power vs. Danger" framework. Dangers are designed using D&D 2024 conditions (Hit Dice, scaled saving throws) to ensure they are narratively impactful without breaking early/late game balance.
4.  **Standardized Elemental Profiles:** Every mutation must follow a 1-primary/3-secondary damage type profile to maintain system consistency.
5.  **Action Economy:** The 'Dual Player' mode for the Shadow Warrior remains a "Hero Character" mechanic for two players sharing one body.
6.  **Terminology & Workspace:** Currency is standardized as "cc," and all legacy volumes are archived in `ReferenceDocuments/`.
7.  **White Shadow Mutation Fix (August 2026):** The Power of the White Shadow mutation was revised. "No penalties in bright light" had zero mechanical effect in D&D 2024 and was replaced with a meaningful prismatic distortion ability (Advantage on Sleight of Hand, 1/Short Rest blinding flash).
8.  **Deity Spell Integration (August 2026):** A "Deity Blessing" class feature was added to both the Savaroen and Shadow Warrior, formalizing the mechanical pathway to obtain a Deity's Cantrip and Unique Spells. All shorthand deity spell descriptions in Chapter 6 were expanded to full D&D 2024 block format.
9.  **Technical Rules & RAW Audit (August 2026):** Resolved missing durations across all chapters (including Warrion `Elemental Trance` 1-minute limit), missing action costs (Animal Spirit, Bonded Weapon, Automaton Assistant), and RAW loopholes.
10. **6-Agent 2024 OP Balance Sweep (August 2026):** Conducted a multi-agent balance sweep. Adjusted Techno Railgun (2d10 Loading), capped spell damage multipliers (Fusion Blast, Potent Spellcasting), re-leveled tier-inappropriate features (Mind Break, Rift Maker), and set Epic Boon prerequisites to Level 19+.
11. **Species Traits & Benchmarks (August 2026):** Genempriea updated to 35ft base speed + *Overclocked Actuators* (Bonus Action Dash PB/LR, matching 2024 Wood Elf/Orc benchmarks). Plunesako expanded to grant dual skills + 1 Origin Feat of choice (matching 2024 Human benchmarks).
