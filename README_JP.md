# 産科婦人科学 Obstetrics-and-Gynecology-PMPH-10edition
<div align="center">

> *「21世紀 医学生ガイド」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 人民衛生出版社『産科婦人科学』第10版に基づく臨床スキルハンドブック — 産科婦人科 187 の核心的臨床スキル
<br>
<br>
<img src="assets/Obstetrics-Gynecology.png" width="260px">
<br>

教科書を丸ごと読む必要はありません<br>
質問を入力するだけで、教科書から自動的に解決策を提供します

<br>

**その他の言語:**

[简体中文](README.md) · [English](README_EN.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## プロジェクト概要

本プロジェクトは、産科婦人科学の中核的知識を体系的に統合し、**15 大カテゴリ** — 妊娠・産科管理、高危険妊娠と合併症、分娩・産後管理、婦人科腫瘍、生殖内分泌・不妊症、子宮内膜症・子宮筋腫、婦人科感染症・炎症、外陰・腟疾患、骨盤底・泌尿婦人科、思春期・閉経周辺期ケア、遺伝・出生前スクリーニングと診断、女性の性健康、解剖・生理・基礎医学、手術・手技、教育・品質管理 — をカバーし、全 **187 項目**の必須臨床スキルを提供します。

**対象読者**：産科婦人科医、助産師、医学生、臨床研修医

**参考教科書**：人民衛生出版社『産科婦人科学』第 10 版

## プロジェクト構造

```
Obstetrics-and-Gynecology-PMPH-10edition/
├── SKILL.md                  # 核心設定 — 187 スキル登録簿
├── README.md                 # 本ファイル — プロジェクト説明・利用ガイド
├── <skill-name>/             # 各スキルの詳細定義
│   └── SKILL.md              #   スキル詳細（使用時期、手順、参考文献）
├── scripts/                  # 実行可能ツールスクリプト
│   ├── skill-search.sh       #   キーワード検索
│   └── skill-report.sh       #   スキル一覧レポート生成
├── config/                   # 設定ファイル
│   └── skill-config.yaml     #   スキル分類・メタデータ設定
└── tests/                    # 検証・テスト
    └── validate-all.sh       #   完全性チェックスクリプト
```

## スキル分類一覧

| 分類 | スキル数 | 説明 |
|------|----------|------|
| 🤰 妊娠・産科管理 | 41 | 産前検診、出産予定日計算、胎位異常、羊水量、TTTS、FGR |
| ⚠️ 高危険妊娠と合併症 | 19 | 子癇前症、GDM、貧血、甲状腺機能低下症、感染症 |
| 🛏️ 分娩・産後管理 | 9 | 産後出血、悪露モニタリング、産褥感染、産後うつ、羊水塞栓症 |
| 🧬 婦人科腫瘍 | 22 | 子宮頸癌、子宮体癌、卵巣癌、外陰癌、絨毛性疾患 |
| 💊 生殖内分泌・不妊症 | 17 | PCOS、無月経、POI、ART、排卵誘発、黄体機能不全 |
| 🔴 子宮内膜症・子宮筋腫 | 5 | 内膜症診断・治療・予防、子宮筋腫管理 |
| 🦠 婦人科感染症・炎症 | 9 | 子宮頸管炎、PID、性器結核、HPV、HIV母子感染予防 |
| 🔵 外陰・腟疾患 | 7 | 硬化性苔癬、萎縮性腟炎、帯下異常、性器出血 |
| 🩺 骨盤底・泌尿婦人科 | 4 | 腹圧性尿失禁、POP-Q、尿瘻、卵管通水検査 |
| 🌸 思春期・閉経周辺期・老年婦人科 | 5 | 思春期評価、閉経周辺期AUB、MHT、ターナー症候群 |
| 🧪 遺伝・出生前スクリーニングと診断 | 11 | 染色体異数性スクリーニング、羊水穿刺、GTN層別治療 |
| 💕 女性の性健康と心理 | 4 | 性的機能障害診断・治療、性反応周期、性健康教育 |
| 🫀 解剖・生理・基礎医学 | 8 | 骨盤解剖、生殖器発生、胎盤構造、ホルモン調節 |
| 🔪 手術・手技 | 3 | 腹腔鏡下避妊手術、吸引法、子宮鏡灌流 |
| 📚 教育・資源・品質管理 | 23 | 教科書構造、品質指標、死亡審査、CA125応用 |

## クイックスタート

### インストール

CLI：
```bash
openclaw skills install obstetrics-gynecology-pmph-10edition
```

### スキルの検索

```bash
# キーワード検索
bash scripts/skill-search.sh 子癇前症

# スキル一覧の生成
bash scripts/skill-report.sh
```

### 使用方法

各スキルは以下の4部構成です：
1. **使用時期** — スキルを発動するタイミング
2. **手順** — 標準化された操作フロー
3. **注意事項** — 禁忌と警告
4. **参考文献** — 詳細な補足資料

## 著者について

**産科婦人科学 第10版 編集委員会** — 人民衛生出版社 全国高等学校5年制本科臨床医学専門 第10次計画教科書

## ライセンス

本プロジェクトの内容は人民衛生出版社『産科婦人科学』第10版に基づき整理されたものであり、学習参考のみを目的としています。

## Star History

<a href="https://www.star-history.com/#Obstetrics-and-Gynecology-PMPH-10edition&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Obstetrics-and-Gynecology-PMPH-10edition&type=Date" />
 </picture>
</a>
