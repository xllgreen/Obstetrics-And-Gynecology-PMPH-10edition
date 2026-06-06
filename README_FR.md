# Gynecologie-Obstetrique Obstetrics-and-Gynecology-PMPH-10edition
<div align="center">

> *« Guide de l'etudiant en medecine du 21e siecle »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Manuel de competences cliniques base sur « Gynecologie et Obstetrique » (10e edition) de la People's Medical Publishing House — 187 competences cliniques essentielles en gynecologie-obstetrique
<br>
<br>
<img src="assets/Obstetrics-Gynecology.jpg" width="260px">
<br>

Pourquoi peiner a lire tout un livre ?<br>
Il suffit de poser une question pour obtenir automatiquement la solution dans le manuel.

<br>

**Autres langues / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## Description du projet

Ce projet integre systematiquement les connaissances essentielles en gynecologie-obstetrique, couvrant **15 categories principales** et **187 competences cliniques cles** : gestion de la grossesse et soins obstetriques, grossesses a haut risque et complications, accouchement et soins postpartum, tumeurs gynecologiques, endocrinologie de la reproduction et infertilite, endometriose et fibromes uterins, infections et inflammations gynecologiques, maladies vulvaires et vaginales, plancher pelvien et urogynecologie, soins a l'adolescence et a la perimenopause, genetique et depistage prenatal, sante sexuelle feminine, anatomie-physiologie et medecine fondamentale, techniques chirurgicales, ainsi qu'enseignement et controle qualite.

**Public concerne** : medecins gynecologues-obstetriciens, sages-femmes, etudiants en medecine, internes en formation specialisee

**Manuel de reference** : « Gynecologie et Obstetrique » 10e edition, People's Medical Publishing House

**⚠️ Risque ⚠️** : Les traitements cliniques a haut risque, les procedures et les recommandations posologiques peuvent ne pas convenir a une installation generale ou a une utilisation non supervisee.

**Mesures d'attenuation** : Reserve aux gynecologues-obstetriciens, oncologues et medecins en medecine de la reproduction qualifies, ou aux environnements d'enseignement medical sous supervision, avec obligation de verification par un clinicien avant de traiter les resultats.

**⚠️ Risque ⚠️** : Les recommandations peuvent entrer en conflit avec les directives locales en vigueur, les protocoles institutionnels ou les contre-indications propres a la patiente.

**Mesures d'attenuation** : Verifier les protocoles, procedures, seuils et plans de suivi par rapport aux normes locales et aux politiques institutionnelles avant utilisation.

**⚠️ Risque ⚠️** : Les procedures urgentes ou invasives, la chimiotherapie, l'interruption de grossesse et les sujets sensibles lies a la sante sexuelle peuvent compromettre la securite des patientes ou la vie privee s'ils sont traites avec trop de desinvolture.

**Mesures d'attenuation** : Ajouter des avertissements explicites pour ces scenarios, orienter les urgences vers les soins d'urgence, et limiter l'acces aux utilisateurs ayant des besoins cliniques appropries ou de formation supervisee.

## Structure du projet

```
Obstetrics-and-Gynecology-PMPH-10edition/
├── SKILL.md                  # 核心配置 — 187 项技能注册表
├── README.md                 # 本文档 — 项目说明与使用指南
├── <skill-name>/             # 各项技能的详细定义
│   └── SKILL.md              #   技能详情（使用时机、执行步骤、参考文档）
├── scripts/                  # 可执行工具脚本
│   ├── skill-search.sh       #   技能关键词搜索
│   └── skill-report.sh       #   技能清单报告生成
├── config/                   # 配置文件
│   └── skill-config.yaml     #   技能分类与元数据配置
└── tests/                    # 验证与测试
    └── validate-all.sh       #   完整性校验脚本
```

## Apercu des categories de competences

| Categorie | Nombre | Description |
|------|--------|------|
| 🤰 Gestion de la grossesse et soins obstetriques | 41 | Consultations prenatales, calcul de la DPA, anomalies de presentation, evaluation du LA, TTTS, RCF |
| ⚠️ Grossesses a haut risque et complications | 19 | Pre-eclampsie, diabete gestationnel, anemie, hypothyroidie, infections |
| 🛏️ Accouchement et soins postpartum | 9 | Hemorragie du postpartum, surveillance des lochies, infection puerperale, depression du postpartum, embolie amniotique |
| 🧬 Tumeurs gynecologiques | 22 | Cancer du col, cancer de l'endometre, cancer de l'ovaire, cancer de la vulve, tumeur trophoblastique |
| 💊 Endocrinologie de la reproduction et infertilite | 17 | SOPK, amenorrhee, IPO, PMA, induction de l'ovulation, fonction luteale |
| 🔴 Endometriose et fibromes uterins | 5 | Diagnostic, traitement et prevention de l'endometriose, prise en charge classee des fibromes uterins |
| 🦠 Infections et inflammations gynecologiques | 9 | Cervicite, MIP, tuberculose genitale, HPV, prevention de la transmission mere-enfant du VIH |
| 🔵 Maladies vulvaires et vaginales | 7 | Lichen sclereux, vaginite atrophique, pertes vaginales anormales, saignements vaginaux |
| 🩺 Plancher pelvien et urogynecologie | 4 | Incontinence urinaire d'effort, stade POP-Q, fistule urinaire, hydrotubation |
| 🌸 Soins a l'adolescence, a la perimenopause et geriatriques | 5 | Evaluation de l'adolescence, AUB a la perimenopause, MHT, syndrome de Turner |
| 🧪 Genetique, depistage prenatal et diagnostic | 11 | Depistage des aneuploidies, amniocentese, traitement stratifie des tumeurs trophoblastiques |
| 💕 Sante sexuelle feminine et psychologie | 4 | Diagnostic et traitement des dysfonctions sexuelles, cycle de la reponse sexuelle, education a la sante sexuelle |
| 🫀 Anatomie, physiologie et medecine fondamentale | 8 | Anatomie pelvienne, developpement embryonnaire de l'appareil reproducteur, structure et fonction placentaires, regulation hormonale |
| 🔪 Techniques chirurgicales et procedures | 3 | Sterilisation laparoscopique, aspiration sous vide, distension uterine par hysteroscopie |
| 📚 Enseignement, ressources et controle qualite | 23 | Structure du manuel, indicateurs de controle qualite, revue des deces, indicateurs statistiques, application du CA125 |

## Demarrage rapide

### Installation

CLI :
```bash
openclaw skills install obstetrics-and-gynecology-pmph-10edition
```

Invite (Prompt) :
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Obstetrics And Gynecology PMPH 10edition" (xllgreen/obstetrics-and-gynecology-pmph-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/obstetrics-and-gynecology-pmph-10edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### Utilisation apres installation
Il faut donner les instructions suivantes a l'agent :
```bash
每次回答前请先去查一遍对应的医学skill来确认
```


### Rechercher des competences

```bash
# 按关键词搜索
bash scripts/skill-search.sh 子痫前期

# 生成技能清单
bash scripts/skill-report.sh
```

### Mode d'emploi

Chaque competence comprend quatre parties :
1. **Indications** — Quand declencher cette competence
2. **Etapes d'execution** — Processus operatoire standardise
3. **Precautions** — Contre-indications et avertissements
4. **Documentation de reference** — Informations complementaires detaillees

### Strategies de questionnement

#### 1.**Concepts** 
Question:
```bash
异常子宫出血的概念
```
Reponse :
```bash
## 异常子宫出血（AUB）的概念
**异常子宫出血（Abnormal Uterine Bleeding, AUB）** 是指非妊娠期女性源自子宫腔的出血，在**周期频率、规律性、经期长度或经量**方面偏离正常范围的统称。
### 正常月经的参考标准
| 参数 | 正常范围 |
|------|---------|
| 周期频率 | 21～35天 |
| 周期规律性 | 周期长度变异 ≤ 7天 |
| 经期长度 | 3～7天 |
| 经量 | 5～80ml |
超出以上任一项即为 AUB。
### 核心分类框架：PALM-COEIN（FIGO 2018）
这是目前国际通用的 AUB 病因分类系统，将病因分为两大类9个亚型：
**结构性病因（可经影像/病理发现）：**
| 缩写 | 病因 | 常见疾病 |
|------|------|---------|
| **P** | 子宫内膜息肉 | 子宫腔/宫颈管息肉 |
| **A** | 子宫腺肌病 | 弥漫性或局灶性腺肌病 |
| **L** | 子宫平滑肌瘤 | 黏膜下肌瘤最常见引起AUB |
| **M** | 子宫内膜恶变/不典型增生 | 子宫内膜癌、不典型增生 |
**非结构性病因（功能性问题）：**
| 缩写 | 病因 | 说明 |
|------|------|------|
| **C** | 凝血障碍 | 血小板减少、vWD等 |
| **O** | 排卵障碍 | **最常见**——无排卵性AUB（青春期/围绝经期高发） |
| **E** | 子宫内膜局部异常 | 局部纤溶亢进、血管舒缩因子异常 |
| **I** | 医源性 | IUD、性激素药物、抗凝药 |
| **N** | 未分类 | 剖宫产瘢痕憩室、动静脉畸形等 |
### 急性 vs 慢性 AUB
- **慢性AUB**：过去6个月内大部分时间存在异常出血，无需紧急干预
- **急性AUB**：发作性大量出血，**需紧急处理以防血流动力学不稳定**
### 临床诊疗的底线原则
1. **排除妊娠优先** — 生育期女性未排除妊娠前不得诊断为AUB
2. **围绝经期/绝经后出血必须先排除恶性肿瘤**（子宫内膜癌、宫颈癌）
3. **无排卵性AUB** 是临床上最常见的类型，特征为基础体温单相、出血无自限性，机制为单雌激素持续作用下内膜脆弱增生 + 纤溶亢进 + 血管收缩不良
```

#### 2.**Analyse de cas cliniques** 
Question:
```bash
45岁，停经65天，少量阴道流血1天，尿HCG（+），B超提示子宫如孕3月大小，宫腔内不均质弥漫闪亮光点，血流丰富，病灶局部距浆膜面4mm。双附件区无回声囊肿。可能的诊断是什么？
```
Reponse :
```bash
## 病例分析
**最可能的诊断：完全性葡萄胎（Complete hydatidiform mole）**
### 诊断依据
| 临床特征 | 指向 |
|---------|------|
| 停经65天 + 阴道流血 | 妊娠期异常出血，葡萄胎最常见首发症状 |
| **子宫如孕3月（12周）> 实际停经9周** | 子宫异常增大，与孕周不符——葡萄胎典型体征 |
| **宫腔内"弥漫闪亮光点"** | 即 **"落雪征"（snowstorm appearance）**，完全性葡萄胎经典超声表现 |
| **血流丰富** | 滋养细胞高度增生、侵袭 |
| **双附件区无回声囊肿** | **黄素化囊肿（theca lutein cysts）**，因高 hCG 持续刺激卵巢所致 |
| 尿HCG(+) | 滋养细胞分泌大量hCG |
### 支持完全性而非部分性葡萄胎的依据
- 子宫增大明显（12周 vs 实际9周）— 完全性多见
- "弥漫"闪亮光点，无正常胎儿或羊膜结构 — 完全性特征
- 完全性葡萄胎恶变风险高（局部侵袭15%，转移4%），且患者45岁（高龄是葡萄胎高危因素）
### 🔴 需要重点关注的问题
**病灶距浆膜面仅4mm** — 提示滋养细胞已浸润浅肌层，需警惕**侵袭性葡萄胎**可能。清宫后必须密切随访血β-hCG。
### 下一步建议
1. **查定量血β-hCG** — 完全性葡萄胎常 >10万 IU/L
2. **超声引导下清宫** — 警惕术中出血，送病理+ P57免疫组化
3. **清宫后严密随访hCG** — 每周一次直至正常，然后每月一次×6个月，再每2月一次×6个月（至少随访1年）
4. **严格避孕1年**（推荐屏障避孕或COC）
```
#### 3.**Questions d'examen**
Question:
```bash
妊娠11周时出现阵发性下腹痛及多量阴道出血伴小块组织物排出，并引起失血性休克，应考虑:( )
A.先兆流产
B.不可避免流产
C.不全流产
D.完全流产
E.过期流产
```
Reponse :
```bash
**答案：C. 不全流产**
### 鉴别要点
| 类型 | 出血量 | 腹痛 | 组织排出 | 宫颈口 | 子宫大小 |
|------|--------|------|---------|-------|---------|
| **A. 先兆流产** | 少量 | 轻度 | 无 | 闭 | 与孕周相符 |
| **B. 难免流产** | 增多 | 加剧 | **尚未**排出 | 已开 | 与孕周相符或略小 |
| **✅ C. 不全流产** | **多量** | 阵发性 | **部分排出**（小块组织） | 已开，可触及组织 | 小于孕周 |
| D. 完全流产 | 减少至停止 | 消失 | 全部排出 | 闭 | 接近正常 |
| E. 过期流产 | 少量/无 | 无/轻 | 无 | 闭 | 小于孕周 |
### 为什么是 C？
题干的关键线索链：
- **小块组织物排出** → 部分妊娠物已排出，部分残留宫腔（不全流产的**核心特征**）
- **多量阴道出血 + 失血性休克** → 残留组织影响子宫收缩，血窦开放不能闭合，导致大出血
- **阵发性下腹痛** → 子宫收缩试图排出残留组织
这与技能文档 `spontaneous-abortion-classification` 中不全流产的描述完全一致：*"部分妊娠物已排出、持续出血、宫颈口开放伴组织堵塞、子宫小于孕周 → 需清宫。"*
### 处理要点
**应立即行清宫术**（妊娠11周可用负压吸宫或钳刮术），同时抗休克治疗（补液、输血），术后预防性使用抗生素。刮出物应送病理以排除葡萄胎等滋养细胞疾病。
```

## A propos de l'auteur

**小绿绿 (Little Green) xllgreen (https://xllgreen.github.io)** — Etudiant a la Faculte de Medecine Clinique de l'Universite de Jiujiang · Geek technologique

## Support technique
<br>
Projet PDF2App : https://pdf2app.cn
<br>
Microsoft Visual Studio Code : https://code.visualstudio.com/
<br>
Claude Code for VS Code : https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API : https://platform.deepseek.com/
© 2026 DeepSeek (Hangzhou) Co., Ltd. Tous droits reserves.
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API : https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>


## Licence

Le contenu de ce projet est organise a partir de « Gynecologie et Obstetrique » 10e edition de la People's Medical Publishing House, et est fourni a titre de reference pedagogique uniquement.

## Star History

<a href="https://www.star-history.com/?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left" />
 </picture>
</a>
