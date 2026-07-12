# Ancient Manuscripts Library — Knowledge of the Classical & Medieval World

> **A curated, Alexandria-style compendium of classical and medieval manuscripts across civilizations** — zoology, botany, materials, human nature, and the unseen. Each guide aggregates the most influential historical sources on a domain, organized by tradition, with modern-equivalent mappings so the wisdom stays alive and queryable.

**Library of Alexandria ↔ Ancient Manuscripts ↔ Cross-Cultural Knowledge ↔ Living Tradition** — a structured corpus of humanity's classical written knowledge, mapped onto the modern disciplines it foreshadowed.

---

## Repository Structure — 6 Categories

```
ancient-manuscripts-library/
├── 00-Library-Framework/        # 02 docs — domain taxonomy + covered/planned checklist
├── 01-Animals/                  # 01 doc  — zoology, bestiaries, mythical creatures
├── 02-Plants-Botany/            # 01 doc  — botany, herbals, agriculture, sacred plants
├── 03-Materials-Mineralogy/     # 01 doc  — minerals, metals, alchemy, gemology
├── 04-Human-Behavior/           # 01 doc  — psychology, ethics, character, leadership
├── 05-Jinn-Unseen/              # 01 doc  — jinn, spirits, cosmology, esoterica
│
├── README.md                    # ← You are here
├── CATALOG.md                   # ← Full structure map (auto-maintained)
├── .gitignore
└── .qdrant-initialized
```

---

## Library at a Glance

| Metric | Value |
|:-------|:------|
| **📄 Knowledge Documents** | **7** markdown files |
| **🗂️ Topic Categories** | **6** (1 framework + 5 domains) |
| **🌍 Traditions Covered** | Islamic, Greek, Roman, Indian, Chinese, Egyptian, Mesopotamian, European medieval |
| **📐 Format** | Self-contained markdown guides, cross-linked by `README.md` index per folder |
| **🗺️ Expansion Taxonomy** | 60+ planned domains (`00-Library-Framework/taxonomy.md`) |
| **📡 Last Updated** | 2026-07-12 |
| **🔓 License** | Open Knowledge — Public Repository |

---

## Deep-Dive Index by Category

### Framework
- **00-Library-Framework** — the master `taxonomy.md` (60+ knowledge domains) and `build-checklist.md` (which domains are covered ✅ vs planned). Use these to expand the library systematically.

### Natural World
- **01-Animals** — *Ancient Manuscripts — Animals, Mythical Creatures & Zoological Knowledge*: al-Jāḥiẓ's *Kitāb al-Ḥayawān*, Aristotle's *Historia Animalium*, Pliny's *Naturalis Historia*, medieval bestiaries, *Pañcatantra*, *Shan Hai Jing*, and more.
- **02-Plants-Botany** — *Ancient Manuscripts — Plants, Trees & Botanical Knowledge*: al-Dinawari's *Kitāb al-Nabāt*, Dioscorides' *De Materia Medica*, Theophrastus, *Bencao Gangmu*, esoteric botany in *Shams al-Maʿārif*.
- **03-Materials-Mineralogy** — *Ancient Manuscripts — Materials, Minerals & Metals*: al-Bīrūnī's *Kitāb al-Jamāhir*, Jabirian alchemy, Theophrastus *On Stones*, Agricola's *De Re Metallica*, *Tiangong Kaiwu*.

### Human & Unseen
- **04-Human-Behavior** — *Ancient Manuscripts — Human Behavior & Character*: al-Ghazālī's *Iḥyāʾ*, Aristotle's *Nicomachean Ethics*, Marcus Aurelius, Confucius, *Bhagavad Gita*, with a cross-reference table and suggested reading order.
- **05-Jinn-Unseen** — *Ancient Manuscripts — Jinn, Spirits & the Unseen*: Qur'anic sources, Hadith, classical *tafsīr*, *ʿAjāʾib al-Makhlūqāt*, *Shams al-Maʿārif*, *Picatrix*, Sufi cosmology.

---

## Document Shape

Every domain folder contains:

- A **`README.md` index** listing each document with its title and a one-line scope.
- One or more **curated guide `.md` files**, each following a consistent structure:
  - `> Overview` blockquote (what the domain is and why it was documented)
  - Sources grouped **by civilization/tradition** (`# 1. Islamic Golden Age`, `# 2. Ancient Greece`, …)
  - Per-source **Focus / Topics / Modern Equivalent** sections
  - A closing **Major Themes** synthesis and (where relevant) **Suggested Reading Order** + **Cross-Reference Table**

This makes each guide self-contained and comparable across cultures.

---

## How to Read

1. **👁️ Browse online** — open the repository on GitHub and navigate the numbered directories.
2. **🏛️ Start from a domain** — open `01-Animals/README.md` (or any folder) and pick a guide.
3. **🧭 Plan expansion** — read `00-Library-Framework/taxonomy.md` to see the full 60+ domain map, then `build-checklist.md` for what's already covered.

---

## Roadmap

- [x] 5 curated cross-cultural manuscript guides (Animals, Plants, Materials, Human Behavior, Jinn/Unseen)
- [x] Master taxonomy of 60+ knowledge domains
- [x] Covered/planned expansion checklist
- [ ] Fungi & Marine Life guides
- [ ] Medicine / Anatomy / Physiology guides
- [ ] Astronomy & Cosmology guides
- [ ] Philosophy, Mathematics, Engineering guides
- [ ] Per-domain sub-folders with deeper primary-source excerpts
- [ ] Obsidian vault + Qdrant brain integration (mirror of `esoteric-alexandria` pattern)
- [ ] Automated gap-analysis cron (flag taxonomy domains with no guide yet)

---

## Contributing

The library grows through collective effort.

- **Add a guide** — drop a new `ancient-manuscripts-*.md` into the relevant numbered folder and add it to that folder's `README.md` index.
- **Add a domain** — if a taxonomy domain has no folder yet, create `NN-Name/` with a `README.md` and open a PR; update `build-checklist.md` to mark it ✅.
- **Improve a guide** — extend any document with newer scholarship, more traditions, or better cross-references.
- **Report a gap** — open an issue for a missing domain or source.

> *"The Library of Alexandria burned once. This one is rebuilt, document by document."*

---

**License:** Open Knowledge — Public Repository · Built with ❤️ for every student of the classical and medieval world.
