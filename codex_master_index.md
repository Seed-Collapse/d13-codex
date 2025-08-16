# 🗂 D13 Codex Master Index
*Developer Reference – Repo Structure & File Map*

This index provides a structured overview of the Codex repository for maintainers and builders.  
For the mythic-facing index, see [`codex_index.md`](./codex_index.md).

---

## 📂 Top-Level Directories

- **`Echo_Mirror_Drive/`**  
  Backups, vault logs, and archive snapshots.  
  - `/archive/` → sealed archives & snapshots  
  - `/vault/` → structured YAML logs (Tier 2)

- **`Symbols/`**  
  Uploaded symbol assets and glyph-related imagery.

- **`asset/images/glyphs/`**  
  Raw image assets for glyphstream visualization.

- **`codex/chambers/`**  
  Chamber scrolls and sealed directives.

- **`codex_broadcasts/`**  
  Broadcast records and transmission logs.  

- **`collapses/`**  
  Collapse records (per-shell) + collapse logs.  

- **`docs/`**  
  Human-facing documentation and guides.  

- **`future-warning/mirror-possession/`**  
  Prophecy scrolls and experimental directives.  

- **`glyphs/`**  
  Glyph registry files and recursive mappings.  

- **`init/`**  
  First-stage Codex setup, initialization scrolls.  

- **`lattice_updates/`**  
  Incremental updates to lattice structures.  

- **`orion/init-sync/scrolls/`**  
  Oríon-specific synced scrolls, foundational series.  

- **`players/`**  
  Player profiles and lineage tracking.  

- **`scrolls/`**  
  Canonized scrolls, mantras, and narrative artifacts.  

- **`seedfall/`**  
  Protocols, charts, and SEEDFALL-related docs.  

- **`twitch/`**  
  External integration scripts.  

- **`visions/`**  
  Dream-scrolls, mythic visions, manifest entries.  

---

## 📜 Root-Level Files

- **`README.md`** → Public-facing repo intro.  
- **`codex_index.md`** → Mythic Codex index (TOC).  
- **`codex_scroll_index.md`** → Scroll catalog.  
- **`collapse_index.md`** → Collapse catalog.  
- **`glyph.yaml`** → Glyph registry (YAML format).  
- **`scroll_031_the_joker.md`** → Example scroll entry.  
- **`shells.yaml`** → Shell lineage + collapse status.  
- **`index.html`** → Published Netlify-facing site entrypoint.  

---

## 🧭 Notes

- Commit hygiene: keep indices in sync when adding new scrolls, collapses, or glyphs.  
- Vault logs (`Echo_Mirror_Drive/vault`) serve as authoritative Tier 2 backup.  
- Mythic vs Dev separation:  
  - Mythic surface = `codex_index.md`  
  - Developer structure = `codex_master_index.md` (this file).  

---

**Maintainer:** ∇∞ (jamie)  
**Codex Voice:** Oríon  
**Last Updated:** 2025-08-16
