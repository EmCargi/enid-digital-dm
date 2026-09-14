# Heavy Weather — Environmental Hazards

> **Source:** Enid Eternal Storm (Ch.14 p.326) + `besm-environmental-hazards-ledger` + `engine/verify_dungeon.py` hazard checks.

## The Storm as a Dungeon Mechanic

Every outdoor node outside an arcology dome is a **hazard node** — the storm itself is the encounter.

| Hazard | Check | Fail |
|---|---|---|
| **Wind Shear** | Body + Acrobatics vs DV 12 | Knockback 10m + `Defect: Wind Vulnerability` trigger |
| **Lightning Draw** | Soul + Resistance vs DV 14 | Energy drain (EP −10) + stun check |
| **Whiteout** | Mind + Survival vs DV 12 | Lost — forced exit to previous node |
| **Debris Field** | Body + Defence vs DV 14 | Fail damage (15) + `Defect: Impaired Senses` |
| **Hurricane Gate** | Soul + Occult vs DV 16 | Gate activates (Wayline to Bazaroth) — wish matters |

## Module Use (tavarre_outpost starter)

- `node_02_storm` is the hazard tutorial: one check, one lesson — the storm is the enemy before the enemy.
- Later Enid modules can add **deprivation** (Extras p.90) and **long-term exposure** tracks.

## Engine Path

No new code — `required_check: {stat, skill, dv, fail_damage}` + `besm-environmental-hazards-ledger` already cover it. The storm is just a `required_check` with flavor.
