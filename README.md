# 妇产科学 Obstetrics-and-Gynecology-PMPH-10edition
<div align="center">

> *「21世纪医学生指南」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 基于人民卫生出版社《妇产科学》第10版的临床技能手册 — 187 项妇产科临床核心技能
<br>
<br>
<img src="assets/Obstetrics-Gynecology.jpg" width="260px">
<br>

何必苦苦读一本书<br>
只需输入一个问题，自动从课本中找到解决方案

<br>

**其他语言 / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## 项目简介

本项目系统整合妇产科学领域核心知识，涵盖妊娠与产科管理、高危妊娠与并发症、分娩与产后管理、妇科肿瘤、生殖内分泌与不孕不育、子宫内膜异位症与子宫肌瘤、妇科感染与炎症、外阴与阴道疾病、盆底与泌尿妇科、青春期与围绝经期保健、遗传与产前筛查诊断、女性性健康、解剖生理与基础医学、手术操作技术及教学质控等 **15 大分类**，共 **187 项关键临床技能**。

**适用人群**：妇产科医师、助产士、医学生、住院医师规范化培训学员

**参考教材**：人民卫生出版社《妇产科学》第 10 版

**⚠️风险⚠️**：高风险临床治疗、程序和剂量指导可能不适合一般安装或无监督使用。

**缓解措施**：仅适用于合格的产科妇科、肿瘤科、生殖医学或有监督的医学教育环境，并在处理输出前要求临床医生审核。

**⚠️风险⚠️**：指导可能与当前当地指南、机构规程或患者特定禁忌相冲突。

**缓解措施**：在使用前核实方案、程序、阈值和后续计划是否符合当地最新标准和机构政策。

**⚠️风险⚠️**：紧急、侵入性手术、化疗、终止妊娠以及敏感的性健康话题如果处理得太随意，可能会造成患者安全或隐私的危害。

**缓解措施**：针对这些情景添加明确警告，将紧急情况引导至急诊护理，并限制有适当临床或监督教育需求的用户访问。

## 项目结构

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

## 技能分类一览

| 分类 | 技能数 | 说明 |
|------|--------|------|
| 🤰 妊娠与产科管理 | 41 | 产前检查、预产期计算、胎位异常、羊水量评估、TTTS、FGR |
| ⚠️ 高危妊娠与并发症 | 19 | 子痫前期、妊娠期糖尿病、贫血、甲状腺功能减退、感染 |
| 🛏️ 分娩与产后管理 | 9 | 产后出血、恶露监测、产褥感染、产后抑郁、羊水栓塞 |
| 🧬 妇科肿瘤 | 22 | 宫颈癌、子宫内膜癌、卵巢癌、外阴癌、滋养细胞肿瘤 |
| 💊 生殖内分泌与不孕不育 | 17 | PCOS、闭经、POI、辅助生殖、促排卵、黄体功能 |
| 🔴 子宫内膜异位症与子宫肌瘤 | 5 | 内异症诊断、治疗与预防、子宫肌瘤分类管理 |
| 🦠 妇科感染与炎症 | 9 | 宫颈炎、PID、生殖器结核、HPV、HIV母婴阻断 |
| 🔵 外阴与阴道疾病 | 7 | 硬化性苔藓、萎缩性阴道炎、白带异常、阴道出血 |
| 🩺 盆底与泌尿妇科 | 4 | 压力性尿失禁、POP-Q分度、尿瘘、输卵管通液 |
| 🌸 青春期、围绝经期与老年妇科 | 5 | 青春期评估、围绝经期AUB、MHT、Turner综合征 |
| 🧪 遗传、产前筛查与诊断 | 11 | 非整倍体筛查、羊膜腔穿刺、滋养细胞肿瘤分层治疗 |
| 💕 女性性健康与心理 | 4 | 性功能障碍诊断与治疗、性反应周期、性健康教育 |
| 🫀 解剖、生理与基础医学 | 8 | 盆腔解剖、生殖胚胎发育、胎盘结构与功能、激素调控 |
| 🔪 手术与操作技术 | 3 | 腹腔镜绝育、负压吸引、宫腔镜膨宫 |
| 📚 教学、资源与质控 | 23 | 教材结构、质控指标、死亡评审、统计指标、CA125应用 |

## 快速开始

### 安装

CLI：
```bash
openclaw skills install obstetrics-and-gynecology-pmph-10edition
```

Prompt：
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

### 安装后使用
需要对agent交代以下内容：
```bash
每次回答前请先去查一遍对应的医学skill来确认
```


### 查找技能

```bash
# 按关键词搜索
bash scripts/skill-search.sh 子痫前期

# 生成技能清单
bash scripts/skill-report.sh
```

### 使用方式

每个技能包含四部分内容：
1. **使用时机** — 何时触发该技能
2. **执行步骤** — 标准化操作流程
3. **注意事项** — 禁忌与警示
4. **参考文档** — 详细补充资料

### 提问策略

#### 1.**概念** 
Question:
```bash
异常子宫出血的概念
```
Answer：
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

#### 2.**临床案例分析** 
Question:
```bash
45岁，停经65天，少量阴道流血1天，尿HCG（+），B超提示子宫如孕3月大小，宫腔内不均质弥漫闪亮光点，血流丰富，病灶局部距浆膜面4mm。双附件区无回声囊肿。可能的诊断是什么？
```
Answer：
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
#### 3.**考试题目**
Question:
```bash
妊娠11周时出现阵发性下腹痛及多量阴道出血伴小块组织物排出，并引起失血性休克，应考虑:( )
A.先兆流产
B.不可避免流产
C.不全流产
D.完全流产
E.过期流产
```
Answer：
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

## 关于作者

**小绿绿 xllgreen(https://xllgreen.github.io)** — 九江学院临床医学院学生·科技极客

## 技术支持
<br>
PDF2App项目：https://pdf2app.cn
<br>
Microsoft Visual Studio Code：https://code.visualstudio.com/
<br>
Claude Code for VS Code：https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API：https://platform.deepseek.com/
© 2026 杭州深度求索人工智能基础技术研究有限公司 版权所有
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API：https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>


## 许可证

本项目内容基于人民卫生出版社《妇产科学》第10版整理，仅供学习参考。

## Star History

<a href="https://www.star-history.com/?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left" />
 </picture>
</a>
