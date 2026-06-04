# Obstétrique et Gynécologie Obstetrics-and-Gynecology-PMPH-10edition
<div align="center">

> *「Guide de l'étudiant en médecine du 21e siècle」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Manuel de compétences cliniques basé sur *Obstétrique et Gynécologie* (PMPH, 10e édition) — 187 compétences cliniques essentielles en obstétrique et gynécologie
<br>
<br>
<img src="assets/Obstetrics-Gynecology.png" width="260px">
<br>

Pourquoi peiner à lire tout un manuel ?<br>
Il suffit de poser une question pour obtenir automatiquement la solution tirée du manuel.

<br>

**Autres langues:**

[简体中文](README.md) · [English](README_EN.md) · [日本語](README_JP.md) · [Русский](README_RU.md)

</div>

---

## Présentation du projet

Ce projet intègre systématiquement les connaissances fondamentales en obstétrique et gynécologie, couvrant **15 grandes catégories** — gestion de la grossesse et de l'obstétrique, grossesse à haut risque et complications, gestion de l'accouchement et du postpartum, oncologie gynécologique, endocrinologie de la reproduction et infertilité, endométriose et fibromes utérins, infections et inflammations gynécologiques, maladies vulvaires et vaginales, plancher pelvien et urogynécologie, soins à l'adolescence et à la périménopause, génétique et dépistage prénatal, santé sexuelle féminine, anatomie/physiologie et sciences fondamentales, techniques chirurgicales, et enseignement/contrôle qualité — pour un total de **187 compétences cliniques essentielles**.

**Public cible** : Médecins obstétriciens-gynécologues, sages-femmes, étudiants en médecine, internes en formation

**Manuel de référence** : *Obstétrique et Gynécologie*, 10e édition, People's Medical Publishing House (PMPH)

## Structure du projet

```
Obstetrics-and-Gynecology-PMPH-10edition/
├── SKILL.md                  # Configuration centrale — registre des 187 compétences
├── README.md                 # Ce fichier — description du projet et guide d'utilisation
├── <skill-name>/             # Définition détaillée de chaque compétence
│   └── SKILL.md              #   Quand utiliser, étapes, références
├── scripts/                  # Scripts d'outils exécutables
│   ├── skill-search.sh       #   Recherche par mot-clé
│   └── skill-report.sh       #   Générateur de rapport d'inventaire
├── config/                   # Fichiers de configuration
│   └── skill-config.yaml     #   Catégories et métadonnées des compétences
└── tests/                    # Validation et tests
    └── validate-all.sh       #   Script de vérification d'intégrité
```

## Aperçu des catégories de compétences

| Catégorie | Compétences | Description |
|-----------|-------------|-------------|
| 🤰 Grossesse et gestion obstétricale | 41 | Visites prénatales, calcul de la DPA, malprésentation, liquide amniotique, TTTS, RCF |
| ⚠️ Grossesse à haut risque et complications | 19 | Préeclampsie, DG, anémie, hypothyroïdie, infections |
| 🛏️ Accouchement et gestion postpartum | 9 | Hémorragie postpartum, surveillance des lochies, infection puerpérale, dépression postpartum, embolie amniotique |
| 🧬 Oncologie gynécologique | 22 | Cancers du col, de l'endomètre, de l'ovaire, de la vulve, tumeurs trophoblastiques |
| 💊 Endocrinologie de la reproduction et infertilité | 17 | SOPK, aménorrhée, IOP, ART, induction d'ovulation, phase lutéale |
| 🔴 Endométriose et fibromes utérins | 5 | Diagnostic, traitement et prévention de l'endométriose ; gestion des fibromes |
| 🦠 Infections et inflammations gynécologiques | 9 | Cervicite, PID, tuberculose génitale, HPV, prévention de la transmission VIH |
| 🔵 Maladies vulvaires et vaginales | 7 | Lichen scléreux, vaginite atrophique, pertes anormales, saignements |
| 🩺 Plancher pelvien et urogynécologie | 4 | IUE, stadification POP-Q, fistule urinaire, perméabilité tubaire |
| 🌸 Gynécologie adolescente, périménopause et gériatrique | 5 | Évaluation pubertaire, AUB périménopausique, THM, syndrome de Turner |
| 🧪 Génétique, dépistage et diagnostic prénatal | 11 | Dépistage d'aneuploïdie, amniocentèse, traitement stratifié des GTN |
| 💕 Santé sexuelle et psychologie féminines | 4 | Diagnostic et traitement des FSD, cycle de réponse sexuelle, éducation sexuelle |
| 🫀 Anatomie, physiologie et sciences fondamentales | 8 | Anatomie pelvienne, embryologie génitale, structure placentaire, régulation hormonale |
| 🔪 Techniques chirurgicales et opératoires | 3 | Stérilisation laparoscopique, aspiration, distension hystéroscopique |
| 📚 Enseignement, ressources et contrôle qualité | 23 | Structure du manuel, indicateurs de qualité, revue des décès, CA125 |

## Guide de démarrage rapide

### Installation

CLI :
```bash
openclaw skills install obstetrics-gynecology-pmph-10edition
```

### Recherche de compétences

```bash
# Recherche par mot-clé
bash scripts/skill-search.sh préeclampsie

# Générer l'inventaire des compétences
bash scripts/skill-report.sh
```

### Utilisation

Chaque compétence comprend quatre sections :
1. **Quand l'utiliser** — déclencheurs d'activation
2. **Étapes** — procédure standardisée
3. **Précautions** — contre-indications et avertissements
4. **Références** — documentation complémentaire détaillée

## À propos

**Comité de rédaction d'Obstétrique et Gynécologie, 10e édition** — Manuel national planifié pour le programme quinquennal de premier cycle en médecine clinique, People's Medical Publishing House

## Licence

Ce projet est compilé à partir d'*Obstétrique et Gynécologie*, 10e édition (PMPH), à des fins de référence éducative uniquement.

## Star History

<a href="https://www.star-history.com/#Obstetrics-and-Gynecology-PMPH-10edition&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date" />
 </picture>
</a>
