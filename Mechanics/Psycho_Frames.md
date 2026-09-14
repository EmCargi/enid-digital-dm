# Psycho-Frames & Psycho-Slaves

> **Source:** BESM 4e Chapter 14, p.327 (Enid). One chassis, two doctrines.

## Psycho-Frame (LOA)

- **Chassis:** Humanoid mecha, 15–30m, built from arcology construction tech.
- **Core:** Psychotronic generator — amplifies pilot's psychic aura **10x**.
- **Effects (BESM `Item` / Edge):** Force field (psycho-dynamic shield), gravity neutralisation (limited flight), storm-drawn lightning/wind blasts (Energy Drawback: must be in heavy weather or near a psychic source).
- **Requirement:** Psychic pilot (Mind 7+ or `Defect: Psychic Sensitivity` inverted as a prerequisite).

## Psycho-Slave (Alliance)

- **Chassis:** Same frame, different cockpit — two-crew: **command pilot** (normal) + **psycho-pod** (captive psychic, cybernetically drained).
- **Mechanics:** Same effects, but the psychic in the pod suffers `Defect: Involuntary Servitude` + `Energy Drain` each turn the frame is active. The command pilot makes the checks, the pod pays the cost.
- **Moral hook:** Every psycho-slave has a name. The party can free them (lose the frame) or use them (keep the frame, carry the Defect).

## As a Disc Item

Both variants are a single `Item` entry scoped to `setting_id=enid` — the chassis is one row, the doctrine is a `Defect` swap. Seeded via `seed_besm_catalog("enid")` + one custom Item. No new `engine/models.py` field needed.

## BESM Build Note

Use the existing **Mecha / Item Attribute** (BESM4 p.215 / Extras p.122) — no engine edit. The 10x amplifier is an `Enhancement: Area` + `Enhancement: Potent` on the pilot's psychic Attribute, housed in the Item.
