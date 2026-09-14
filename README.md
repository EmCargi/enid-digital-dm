# 💿 Enid: Heavy Weather — Game Disc for Chronos Core

*The first BESM Anime Multiverse Prime World disc.* Disc 5 in the console-and-disc model — the "safe and solid" demo.

> **Source:** BESM 4e Chapter 14 (Anime Multiverse, pp. 326–327) — Enid, the world of the Eternal Storm. First-party canon, no third-party IP.
> All content is authored from the Chapter 14 hooks + BESM stat ladders. No lorebook to split — the vault is hand-written and regenerable.

---

## 🎮 Boot (when ready)

```text
/setting besm_enid         # swap discs in the TUI
/roster                    # Clearance column (S/A/B/C — mirrors LOA/Global Alliance ranks)
/module tavarre_outpost     # default: 5-node starter (Outpost → Storm → Shrine → Duel → Gate)
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_enid` in `config/settings.json` → `tavarre_outpost.json` (`4f40124` → `besm_enid` on 2026-09-12) |
| **2 · Module** | ✅ `modules/tavarre_outpost.json` (5-node labyrinth, validator-passed at `4c961e3`) |
| **3 · Roster** | ✅ 6 starter characters authored (`Characters/`, 50 CP, `besm_enid` — Vaelen Kor through Lyra Vance) |
| **4 · Economy** | ⏳ seeded catalog + psycho-frame chassis as `Item` |
| **5 · Lore Vault** | 🏗️ `World/` `Characters/` `Factions/` `Locations/` `Mechanics/` (this disc) |

> **Status: SCAFFOLDED** — disc directory + proposal exist. Layers 1–4 next.

## 🗂️ Structure

```
enid-digital-dm/
├── README.md               ← this home page
├── World/                  ← Eternal Storm, Noa Enid, arcologies, heavy weather
├── Characters/             ← LOA psychics, Alliance officers, Skeleton Key, gatekeeper
├── Factions/               ← LOA, Global Alliance, Tavarre neutrals, Bazaroth cults
├── Locations/              ← Tavarre Outpost, Noa Enid, Akronia, dome cities, storm gates
├── Mechanics/              ← Psycho-frames, psycho-slaves, environmental hazards, Waylines
├── Meta/                   ← index / onboarding landing
├── modules/                ← tavarre_outpost.json (starter labyrinth)
└── scripts/build_enid_disc.py ← regenerable build (idempotent, atomic, path-agnostic) — next
```

## 🌪️ The Pitch

Enid, 70 years AES — the Eternal Storm has shattered the world into arcologies and domes. Two superpowers fight over Tavarre, the neutral corridor ideal for orbital launches: **LOA** (psychic arcology, psycho-frame mecha, hyper-psychic gestalt dream) vs **Global Alliance** (anti-psi military, Project Butterfly orbital lasers, psycho-slave mecha). The players are caught in the middle — with a gate to Bazaroth humming in a hurricane's eye.

One mecha chassis, two doctrines. One storm, three ways to read it.

## 📌 Why Enid for the demo

Guild RPG = fantasy quest board. SxM = monster taming. MHA = superhero school. Cyberpunk = street heist. **Enid = post-apoc mecha + psychic war** — the genre gap the console hasn't shown yet, with the smallest new-rules surface (one mecha Item, one hazard table).

---
*Swap the disc, keep the console.*
