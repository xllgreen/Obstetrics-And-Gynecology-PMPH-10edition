# 産婦人科学 Obstetrics-and-Gynecology-PMPH-10edition
<div align="center">

> *「21世紀の医学生ガイド」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 人民衛生出版社『産婦人科学』第10版に基づく臨床スキルハンドブック — 187 の産婦人科臨床中核スキル
<br>
<br>
<img src="assets/Obstetrics-Gynecology.jpg" width="260px">
<br>

一冊の本を苦労して読む必要はありません<br>
質問を一つ入力するだけで、教科書から自動的に解決策を見つけます

<br>

**他の言語 / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## プロジェクト概要

本プロジェクトは産婦人科学分野の中核的知識を体系的に統合し、妊娠と産科管理、ハイリスク妊娠と合併症、分娩と産後管理、婦人科腫瘍、生殖内分泌と不妊不育、子宮内膜症と子宮筋腫、婦人科感染症と炎症、外陰と膣疾患、骨盤底と泌尿婦人科、思春期と閉経周辺期のヘルスケア、遺伝と出生前スクリーニング診断、女性の性健康、解剖生理と基礎医学、手術操作技術および教育品質管理などの **15 大カテゴリ**、計 **187 項目の重要臨床スキル**を網羅しています。

**対象者**：産婦人科医師、助産師、医学生、初期臨床研修医

**参考教材**：人民衛生出版社『産婦人科学』第 10 版

**⚠️リスク⚠️**：高リスクの臨床治療、手順、および用量ガイダンスは、一般インストール環境や監督なしでの使用には適さない場合があります。

**緩和策**：認定を受けた産科婦人科、腫瘍科、生殖医学、または監督下の医学教育環境にのみ適用し、出力を取り扱う前に臨床医のレビューを要求してください。

**⚠️リスク⚠️**：ガイダンスが現在の地域のガイドライン、施設のプロトコル、または患者固有の禁忌と矛盾する可能性があります。

**緩和策**：使用前に、計画、手順、閾値、フォローアップ計画が地域の最新基準および施設の方針に適合していることを確認してください。

**⚠️リスク⚠️**：緊急処置、侵襲的手術、化学療法、妊娠中絶、およびデリケートな性健康に関する話題を軽率に扱うと、患者の安全やプライバシーに害を及ぼす可能性があります。

**緩和策**：これらのシナリオに対して明確な警告を追加し、緊急時は救急医療へ誘導し、適切な臨床または監督下の教育ニーズを持つユーザーのみアクセスを制限してください。

## プロジェクト構造

```
Obstetrics-and-Gynecology-PMPH-10edition/
├── SKILL.md                  # 中核設定 — 187 スキルレジストリ
├── README.md                 # 本ドキュメント — プロジェクト説明と使用ガイド
├── <skill-name>/             # 各スキルの詳細定義
│   └── SKILL.md              #   スキル詳細（使用タイミング、実行手順、参考文書）
├── scripts/                  # 実行可能ツールスクリプト
│   ├── skill-search.sh       #   スキルキーワード検索
│   └── skill-report.sh       #   スキル一覧レポート生成
├── config/                   # 設定ファイル
│   └── skill-config.yaml     #   スキル分類とメタデータ設定
└── tests/                    # 検証とテスト
    └── validate-all.sh       #   完全性検証スクリプト
```

## スキル分類一覧

| カテゴリ | スキル数 | 説明 |
|------|--------|------|
| 🤰 妊娠と産科管理 | 41 | 産前検診、出産予定日計算、胎位異常、羊水量評価、TTTS、FGR |
| ⚠️ ハイリスク妊娠と合併症 | 19 | 子癇前症、妊娠糖尿病、貧血、甲状腺機能低下症、感染症 |
| 🛏️ 分娩と産後管理 | 9 | 産後出血、悪露モニタリング、産褥感染、産後うつ病、羊水塞栓症 |
| 🧬 婦人科腫瘍 | 22 | 子宮頸癌、子宮内膜癌、卵巣癌、外陰癌、絨毛性腫瘍 |
| 💊 生殖内分泌と不妊不育 | 17 | PCOS、無月経、POI、生殖補助医療、排卵誘発、黄体機能 |
| 🔴 子宮内膜症と子宮筋腫 | 5 | 子宮内膜症の診断、治療と予防、子宮筋腫の分類管理 |
| 🦠 婦人科感染症と炎症 | 9 | 子宮頸管炎、PID、性器結核、HPV、HIV母子感染予防 |
| 🔵 外陰と膣疾患 | 7 | 硬化性苔癬、萎縮性腟炎、帯下異常、膣出血 |
| 🩺 骨盤底と泌尿婦人科 | 4 | 腹圧性尿失禁、POP-Q分類、尿瘻、卵管通水 |
| 🌸 思春期、閉経周辺期と老年婦人科 | 5 | 思春期評価、閉経周辺期AUB、MHT、ターナー症候群 |
| 🧪 遺伝、出生前スクリーニングと診断 | 11 | 異数性スクリーニング、羊水穿刺、絨毛性腫瘍の層別治療 |
| 💕 女性の性健康と心理 | 4 | 性機能障害の診断と治療、性反応周期、性健康教育 |
| 🫀 解剖、生理と基礎医学 | 8 | 骨盤解剖、生殖胚発生、胎盤の構造と機能、ホルモン調節 |
| 🔪 手術と操作技術 | 3 | 腹腔鏡下不妊手術、吸引法、子宮鏡下拡張 |
| 📚 教育、リソースと品質管理 | 23 | 教材構成、品質管理指標、死亡審査、統計指標、CA125の応用 |

## クイックスタート

### インストール

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

### インストール後の使用方法
エージェントに以下の内容を指示してください：
```bash
每次回答前请先去查一遍对应的医学skill来确认
```


### スキルの検索

```bash
# キーワードで検索
bash scripts/skill-search.sh 子痫前期

# スキル一覧の生成
bash scripts/skill-report.sh
```

### 使用方法

各スキルは4つの部分で構成されています：
1. **使用タイミング** — いつこのスキルを発動するか
2. **実行手順** — 標準化された操作フロー
3. **注意事項** — 禁忌と警告
4. **参考文書** — 詳細な補足資料

### 質問の仕方

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

#### 2.**臨床ケース分析** 
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
#### 3.**試験問題**
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

## 著者について

**小绿绿 (リトルグリーン) xllgreen(https://xllgreen.github.io)** — 九江学院臨床医学院 学生・テクノロジーギーク

## テクノロジーサポート
<br>
PDF2Appプロジェクト：https://pdf2app.cn
<br>
Microsoft Visual Studio Code：https://code.visualstudio.com/
<br>
Claude Code for VS Code：https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API：https://platform.deepseek.com/
© 2026 杭州深度求索人工智能基礎技術研究有限公司 All rights reserved
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API：https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>


## ライセンス

本プロジェクトの内容は、人民衛生出版社『産婦人科学』第10版に基づいて整理されており、学習参考用としてのみ提供されます。

## Star History

<a href="https://www.star-history.com/?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=date&legend=top-left" />
 </picture>
</a>
