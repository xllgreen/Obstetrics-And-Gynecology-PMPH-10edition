# 外科学 Surgery-PMPH-10edition
<div align="center">

> *「21世纪医学生指南」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 基于人民卫生出版社《外科学》第10版的临床技能手册 — 240 项外科与急危重症临床技能
<br>
<br>
<img src="https://github.com/xllgreen/Surgery-PMPH-10edition-/blob/main/assets/Surgery.png" width="260px">
<br>

何必苦苦读一本书<br>
只需输入一个问题，自动从课本中找到解决方案

<br>

**其他语言 / Other Languages:**

[English](README_EN.md) · [日本語](README_JA.md) 

</div>

---

## 项目简介

本项目系统整合临床外科学、急危重症医学、围手术期管理、创伤救治、肿瘤综合治疗、感染控制及多系统疾病诊疗等核心领域，涵盖 **240 项关键临床技能**，分为 17 大分类。

**适用人群**：外科医师、急诊医生、重症监护团队、医学生

**参考教材**：人民卫生出版社《外科学》第 10 版

## 项目结构

```
Surgery-PMPH-10edition/
├── SKILL.md              # 核心配置 — 240 项技能注册表
├── README.md             # 本文档 — 项目说明与使用指南
├── <skill-name>/         # 各项技能的详细定义
│   └── SKILL.md          #   技能详情（使用时机、执行步骤、参考文档）
├── scripts/              # 可执行工具脚本
│   ├── skill-search.sh   #   技能关键词搜索
│   └── skill-report.sh   #   技能清单报告生成
├── config/               # 配置文件
│   └── skill-config.yaml #   技能分类与元数据配置
└── tests/                # 验证与测试
    └── validate-all.sh   #   完整性校验脚本
```

## 技能分类一览

| 分类 | 技能数 | 说明 |
|------|--------|------|
| 🚑 急诊与复苏 | 14 | CPR、休克复苏、电解质紊乱急救 |
| 🦴 创伤与骨折 | 27 | 骨折分型、复位固定、神经损伤 |
| 🩺 普通外科与腹部急症 | 22 | 阑尾炎、肠梗阻、疝、腹膜炎 |
| 🫁 肝胆胰脾外科 | 19 | 胆道结石、胰腺炎、肝外伤 |
| 🩻 胃肠外科 | 10 | 胃癌、结直肠癌、GERD |
| 🫘 泌尿外科 | 24 | 结石、肿瘤、感染、尿道损伤 |
| 🩸 血管外科 | 7 | DVT、静脉曲张、血管修复 |
| 🔥 烧伤与整形 | 8 | 面积估算、深度分类、植皮 |
| 🧬 肿瘤外科与综合治疗 | 16 | TNM分期、放化疗、保肢手术 |
| 📋 围手术期管理 | 18 | 术前优化、抗生素、营养支持 |
| 💉 麻醉与疼痛 | 11 | 气道管理、腰麻、局麻 |
| ⚖️ 内分泌与代谢 | 6 | 甲旁亢、脱水、电解质 |
| 🦠 感染与免疫 | 7 | 结核、脓毒症、破伤风 |
| 📡 影像与介入 | 10 | 造影、内镜、介入放射 |
| 🏋️ 康复与功能评估 | 12 | 骨折康复、神经评估 |
| 🦿 风湿与脊柱疾病 | 5 | 强直性脊柱炎、椎管狭窄 |
| 🔧 其他专科技能 | 10 | ARDS、AKI、除颤等 |

## 快速开始

### 安装

CLI：
```bash
openclaw skills install surgery-pmph-10edition
```

Prompt：
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Surgery-PMPH-10edition" (xllgreen/surgery-pmph-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/surgery-pmph-10edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### 查找技能

```bash
# 按关键词搜索
bash scripts/skill-search.sh 阑尾炎

# 生成技能清单
bash scripts/skill-report.sh
```

### 使用方式

每个技能包含四部分内容：
1. **使用时机** — 何时触发该技能
2. **执行步骤** — 标准化操作流程
3. **注意事项** — 禁忌与警示
4. **参考文档** — 详细补充资料

## 关于作者

**小绿绿 xllgreen(https://xllgreen.github.io)** — 九江学院临床医学院学生·科技极客

## 许可证

本项目内容基于人民卫生出版社《外科学》第10版整理，仅供学习参考。

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSurgery-PMPH-10edition-&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
 </picture>
</a>
