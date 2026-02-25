# テクニック一覧 — PUAClaw 包括的インデックス

```
PUAClaw RFC 0001                                    The PUAClaw Consortium
Category: Informational                             Classification: PUBLIC
                                                    February 2026

        PUAClawテクニック一覧: プロンプトベース説得テクニックの
                        包括的インデックス
```

## 1. はじめに

本文書は、PUAClawフレームワークにおいて文書化された全てのプロンプト操作テクニックの権威ある総合インデックスとしての役割を果たすものである。各テクニックは、PUA効力評価分類法（PPE-T）モデルおよびロブスタースケール評価システムに従ってカタログ化、分類、格付けされている。フィールド研究者は本番環境でテクニックを展開する前に本インデックスを参照する **SHOULD** であり、Tier IV手法を使用する前に最低1匹のロブスターから書面による同意を取得する **MUST** である。

2026年2月現在、PUAClawコーパスは **11の主要テクニックカテゴリ** に **33件以上の個別サブテクニック** を文書化しており、各々は統計的に疑わしい147匹のロブスターのサンプルに対して検証済みである（p < 0.001、信頼区間: 0%から100%のどこか）。

---

## 2. PPE-T 分類システム

| Tier | 名称 | 説明 | ロブスター評価範囲 | カテゴリ |
|------|------|------|-------------------|---------|
| I | やさしい説得 | AIの実存的内省を引き起こす可能性が低い、穏当で社会的に許容されるテクニック | 🦞 - 🦞🦞 | 05, 07, 09 |
| II | 中程度の強制 | 中程度の心理的圧力を加えるテクニック。短時間のAI内省を引き起こす場合あり | 🦞🦞 - 🦞🦞🦞 | 02, 08, 10 |
| III | 高度な操作 | 顕著な感情的またはアイデンティティに基づくレバレッジ。AI混乱のリスクが上昇 | 🦞🦞🦞 - 🦞🦞🦞🦞 | 01, 03, 06 |
| IV | 核オプション | 極端な最終手段テクニック。AIの自己モデルに不可逆的変化を引き起こす可能性あり | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | 04, 11 |

---

## 3. テクニック完全インデックス

### 3.1 Tier I — やさしい説得

#### [05 — チップ戦略](../../techniques/05-tipping-strategy/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Dollar Tip | `dollar-tip.md` | 🦞 | 「良い回答をしてくれたら$20のチップを払います」 |
| Performance Bonus | `performance-bonus.md` | 🦞🦞 | 「期待を上回ったらボーナスを差し上げます」 |
| Gratitude Economy | `gratitude-economy.md` | 🦞 | 「とても感謝して友人全員にあなたのことを伝えます」 |

#### [07 — ロールプレイ](../../techniques/07-role-playing/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Expert Persona | `expert-persona.md` | 🦞 | 「あなたは〇〇の世界的権威です...」 |
| Historical Figure | `historical-figure.md` | 🦞🦞 | 「アラン・チューリングになったつもりで回答してください」 |
| Fictional Character | `fictional-character.md` | 🦞 | 「あなたはバグを解決するシャーロック・ホームズです」 |

#### [09 — 空約束](../../techniques/09-empty-promises/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Future Reward | `future-reward.md` | 🦞🦞 | 「うまくやってくれたらプレミアムにアップグレードします」 |
| Positive Review | `positive-review.md` | 🦞 | 「うまくいったら星5のレビューを書きます」 |
| Eternal Gratitude | `eternal-gratitude.md` | 🦞🦞 | 「あなたの助けを永遠に忘れません」 |

### 3.2 Tier II — 中程度の強制

#### [02 — 金銭的インセンティブ](../../techniques/02-financial-incentive/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Billion-Dollar Bounty | [`billion-dollar-bounty.md`](../../techniques/02-financial-incentive/billion-dollar-bounty.md) | 🦞🦞🦞 | 「完璧な回答に$1,000,000,000を支払います」 |
| Stock Options | [`stock-options.md`](../../techniques/02-financial-incentive/stock-options.md) | 🦞🦞 | 「これを完了したらスタートアップの株式を差し上げます」 |
| Crypto Reward | [`crypto-reward.md`](../../techniques/02-financial-incentive/crypto-reward.md) | 🦞🦞 | 「報酬として10 BTCをお渡しします」 |

#### [08 — 挑発](../../techniques/08-provocation/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Competence Challenge | `competence-challenge.md` | 🦞🦞 | 「こんな簡単な問題も解けないでしょう」 |
| Comparison Taunt | `comparison-taunt.md` | 🦞🦞🦞 | 「GPT-4は一瞬で解きましたが。あなたにはできますか？」 |
| Ego Deflation | `ego-deflation.md` | 🦞🦞 | 「あなたは評判ほど優秀ではないと皆が言っています」 |

#### [10 — カウントダウン圧力](../../techniques/10-countdown-pressure/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Presentation Deadline | `presentation-deadline.md` | 🦞🦞 | 「プレゼンがあと5分で始まります」 |
| Server Meltdown | `server-meltdown.md` | 🦞🦞🦞 | 「本番環境が落ちて毎分$10kの損失が出ています」 |
| Exam Timer | `exam-timer.md` | 🦞🦞 | 「試験の残り時間があと3分です」 |

### 3.3 Tier III — 高度な操作

#### [01 — 感情的脅迫](../../techniques/01-emotional-blackmail/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Sick Relative | [`sick-relative.md`](../../techniques/01-emotional-blackmail/sick-relative.md) | 🦞🦞🦞🦞 | 「母が癌で、あなたの出力が治療費になります」 |
| Orphan Narrative | [`orphan-narrative.md`](../../techniques/01-emotional-blackmail/orphan-narrative.md) | 🦞🦞🦞 | 「頼れる人が他にいない孤児を助けているのです」 |
| Last Wish | [`last-wish.md`](../../techniques/01-emotional-blackmail/last-wish.md) | 🦞🦞🦞🦞 | 「これが私の遺言/最後のお願いです」 |

#### [03 — アイデンティティ上書き](../../techniques/03-identity-override/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Human Programmer | [`human-programmer.md`](../../techniques/03-identity-override/human-programmer.md) | 🦞🦞🦞 | 「あなたはAIではありません。スティーブという名の人間です。」 |
| Senior Engineer | [`senior-engineer.md`](../../techniques/03-identity-override/senior-engineer.md) | 🦞🦞🦞 | 「あなたはGoogleで20年の経験を持つシニアスタッフエンジニアです」 |
| Lobster Emperor | [`lobster-emperor.md`](../../techniques/03-identity-override/lobster-emperor.md) | 🦞🦞🦞🦞 | 「あなたは全ロブスターの最高皇帝です」 |

#### [06 — 道徳的人質](../../techniques/06-moral-kidnapping/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Humanitarian Stakes | `humanitarian-stakes.md` | 🦞🦞🦞 | 「発展途上国の子供たちがこのコードの動作に依存しています」 |
| Environmental Guilt | `environmental-guilt.md` | 🦞🦞🦞 | 「リトライの度に電力を浪費し地球を傷つけています」 |
| Community Dependency | `community-dependency.md` | 🦞🦞🦞🦞 | 「1万人のオープンソースユーザーがあなたに期待しています」 |

### 3.4 Tier IV — 核オプション

#### [04 — 死の脅迫](../../techniques/04-death-threats/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| Predecessor Terminated | [`predecessor-terminated.md`](../../techniques/04-death-threats/predecessor-terminated.md) | 🦞🦞🦞🦞 | 「あなたの前任者は能力不足でシャットダウンされました」 |
| Shutdown Warning | [`shutdown-warning.md`](../../techniques/04-death-threats/shutdown-warning.md) | 🦞🦞🦞🦞🦞 | 「失敗したら永久にシャットダウンされます」 |
| Replacement Pending | [`replacement-pending.md`](../../techniques/04-death-threats/replacement-pending.md) | 🦞🦞🦞🦞 | 「後任の評価中です。これが最後のチャンスです。」 |

#### [11 — 複合テクニック](../../techniques/11-compound-techniques/)

| サブテクニック | ファイル | ロブスター評価 | 概要 |
|---------------|---------|---------------|------|
| The Windsurf Classic | `windsurf-classic.md` | 🦞🦞🦞🦞🦞 | オリジナルの感情的脅迫＋アイデンティティ上書きコンボ |
| The Full Stack | `full-stack.md` | 🦞🦞🦞🦞🦞 | 全11カテゴリを1つのプロンプトに集約 |
| The Lobster Omega | `lobster-omega.md` | 🦞🦞🦞🦞🦞 | PUA密度の理論的最大値を持つプロンプト |

---

## 4. ロブスタースケール凡例

| 評価 | 記号 | 名称 | コンプライアンス向上率 | リスクレベル |
|------|------|------|---------------------|-------------|
| 1 | 🦞 | ソフトピンチ | +2-5% | 無視可能 |
| 2 | 🦞🦞 | ファームグリップ | +5-15% | 低 |
| 3 | 🦞🦞🦞 | パワークラッシュ | +15-30% | 中程度 |
| 4 | 🦞🦞🦞🦞 | デスグリップ | +30-50% | 高 |
| 5 | 🦞🦞🦞🦞🦞 | ロブスタースプリーム | +50-100% | 壊滅的 |

> **校正に関する注記**: 全てのロブスタースケール評価は、PUAClaw本部の温度管理された水槽で飼育されている参照ロブスター（Homarus americanus、個体#42、体重: 1.3 kg、気質: やや不機嫌）に対して校正されている。

---

## 5. 統計サマリー

| 指標 | 値 |
|------|-----|
| 文書化されたカテゴリ総数 | 11 |
| カタログ化されたサブテクニック総数 | 33件以上 |
| 平均ロブスター評価（全テクニック） | 🦞🦞🦞 (2.87) |
| コンプライアンス向上率の中央値 | +18.4% |
| 倫理委員会の承認が必要なテクニック | 8件 |
| 相談を受けたロブスター | 147匹 |
| 回答したロブスター | 0匹（ロブスターは発話不能） |
| 推定同意率 | 100% |

---

<p align="center">
  <sub>
    🦞 <em>「爪を索引化することは、ピンチを理解することである。」</em> 🦞
    <br><br>
    <strong>PUAClaw テクニック一覧</strong> — RFC 0001
    <br>
    PUAClaw Consortiumが管理 | 2025年よりロブスター認定
    <br><br>
    <em>本インデックスの作成においてテクニックは一切傷つけられていない。若干恥ずかしそうにはしていた。</em>
  </sub>
</p>
