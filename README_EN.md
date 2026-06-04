# Obstetrics and Gynecology Obstetrics-and-Gynecology-PMPH-10edition
<div align="center">

> *「21st Century Medical Student Guide」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Clinical skills handbook based on *Obstetrics and Gynecology* (PMPH, 10th Edition) — 187 core clinical skills in obstetrics & gynecology
<br>
<br>
<img src="assets/Obstetrics-Gynecology.png" width="260px">
<br>

Why struggle through a whole textbook?<br>
Just ask a question, and the solution is retrieved from the textbook automatically.

<br>

**Other Languages:**

[简体中文](README.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## Introduction

This project systematically integrates core knowledge in obstetrics and gynecology, covering **15 major categories** — pregnancy & obstetric management, high-risk pregnancy & complications, delivery & postpartum management, gynecologic oncology, reproductive endocrinology & infertility, endometriosis & uterine fibroids, gynecologic infection & inflammation, vulvar & vaginal diseases, pelvic floor & urogynecology, adolescent & perimenopausal care, genetics & prenatal screening/diagnosis, female sexual health, anatomy/physiology & basic medical sciences, surgical techniques, and teaching/quality control — for a total of **187 essential clinical skills**.

**Target Audience**: Ob/Gyn physicians, midwives, medical students, resident trainees

**Reference Textbook**: *Obstetrics and Gynecology*, 10th Edition, People's Medical Publishing House (PMPH)

## Project Structure

```
Obstetrics-and-Gynecology-PMPH-10edition/
├── SKILL.md                  # Core config — registry of 187 skills
├── README.md                 # This file — project description & usage guide
├── <skill-name>/             # Detailed definition for each skill
│   └── SKILL.md              #   When to use, steps, references
├── scripts/                  # Executable tool scripts
│   ├── skill-search.sh       #   Keyword skill search
│   └── skill-report.sh       #   Skill inventory report generator
├── config/                   # Configuration files
│   └── skill-config.yaml     #   Skill categories & metadata config
└── tests/                    # Validation & testing
    └── validate-all.sh       #   Integrity check script
```

## Skill Categories Overview

| Category | Skills | Description |
|----------|--------|-------------|
| 🤰 Pregnancy & Obstetric Management | 41 | Prenatal visits, EDD calculation, malpresentation, amniotic fluid, TTTS, FGR |
| ⚠️ High-Risk Pregnancy & Complications | 19 | Preeclampsia, GDM, anemia, hypothyroidism, infections |
| 🛏️ Delivery & Postpartum Management | 9 | PPH, lochia monitoring, puerperal infection, PPD, amniotic fluid embolism |
| 🧬 Gynecologic Oncology | 22 | Cervical, endometrial, ovarian, vulvar cancers, GTN |
| 💊 Reproductive Endocrinology & Infertility | 17 | PCOS, amenorrhea, POI, ART, ovulation induction, luteal phase |
| 🔴 Endometriosis & Uterine Fibroids | 5 | Diagnosis, treatment & prevention of endometriosis; fibroid management |
| 🦠 Gynecologic Infection & Inflammation | 9 | Cervicitis, PID, genital TB, HPV, HIV MTCT prevention |
| 🔵 Vulvar & Vaginal Diseases | 7 | Lichen sclerosus, atrophic vaginitis, abnormal discharge, bleeding |
| 🩺 Pelvic Floor & Urogynecology | 4 | SUI, POP-Q staging, urinary fistula, tubal patency |
| 🌸 Adolescent, Perimenopausal & Geriatric Gynecology | 5 | Pubertal assessment, perimenopausal AUB, MHT, Turner syndrome |
| 🧪 Genetics, Prenatal Screening & Diagnosis | 11 | Aneuploidy screening, amniocentesis, GTN stratified therapy |
| 💕 Female Sexual Health & Psychology | 4 | FSD diagnosis & treatment, sexual response cycle, sex education |
| 🫀 Anatomy, Physiology & Basic Sciences | 8 | Pelvic anatomy, embryology, placental structure, hormone regulation |
| 🔪 Surgical & Operative Techniques | 3 | Laparoscopic sterilization, vacuum aspiration, hysteroscopic distension |
| 📚 Teaching, Resources & Quality Control | 23 | Textbook structure, QC indicators, mortality review, CA125 |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install obstetrics-gynecology-pmph-10edition
```

### Finding Skills

```bash
# Search by keyword
bash scripts/skill-search.sh preeclampsia

# Generate skill inventory
bash scripts/skill-report.sh
```

### How to Use

Each skill includes four sections:
1. **When to Use** — triggers for activating the skill
2. **Steps** — standardized workflow
3. **Cautions** — contraindications & warnings
4. **References** — detailed supplementary material

## About

**Editorial Board of Obstetrics and Gynecology, 10th Edition** — National Planning Textbook for Five-Year Undergraduate Clinical Medicine, People's Medical Publishing House

## License

This project is compiled based on *Obstetrics and Gynecology*, 10th Edition (PMPH), for educational reference only.

## Star History

<a href="https://www.star-history.com/#Obstetrics-and-Gynecology-PMPH-10edition&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date" />
 </picture>
</a>
