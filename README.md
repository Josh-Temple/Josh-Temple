# Josh — 公共実務 × DX / AI活用

地方自治体職員としての実務を軸に、制度・情報・業務の複雑さをどう整理し、デジタル技術で扱いやすくするかを探究しています。

ここでは、**公開一次資料の調査 → 情報・データ設計 → AIを使った実装 → 検証・改善**に取り組む個人プロジェクトを紹介します。所属組織の公式事業・業務成果とは区別しています。

**Public-sector practitioner exploring digital transformation, AI-enabled workflow design, research, implementation and verification.**

## まず見る3件

| プロジェクト / 公開サイト | 問題と取り組み | Repositoryで確認できること |
|---|---|---|
| [Kaigo Rules](https://kaigo-rules.vercel.app/databases) | 分散する介護制度の公式資料を、実務の疑問から根拠へ辿れる構造へ | [制度・データ設計、独立機械照合、確認状態の分離](https://github.com/Josh-Temple/kaigo-rules) |
| [公共AI調達](https://josh-temple.github.io/public-sector-ai-procurement-japan/) | 自治体の生成AI調達を、仕様・質疑・評価・公開結果まで一次資料で比較 | [出典・有効要件・証拠の限界、CI、比較実験](https://github.com/Josh-Temple/public-sector-ai-procurement-japan) |
| [Can AI Do This?](https://josh-temple.github.io/can-ai-do-this/) | 「この作業をAIでできるか」を、条件と根拠付きで判断できる形へ | [タスク中心の情報設計、公式資料と実測の区別、鮮度監視](https://github.com/Josh-Temple/can-ai-do-this) |

## 業務設計・研究・小さな実装

- **[AI Business Transformation](https://ai-business-transformation-nine.vercel.app)** — 業務選定、標準化、人間による確認、効果測定を考える知見の入口。[Repository](https://github.com/Josh-Temple/ai-business-transformation)。初期コンテンツであり、顧客への導入実績を示すものではありません。
- **[Studio Lab](https://josh-temple.github.io/studio-lab-research/)** — 公開可能な研究・プロジェクト・方法の案内。[Repository](https://github.com/Josh-Temple/studio-lab-research)。研究の採否基準・公開範囲を確認できます。非公開の運用ログを公開するものではありません。
- **[Instant Radio](https://github.com/Josh-Temple/instant-radio)** — 貼り付けた文章をブラウザの読み上げで連続再生する小さなWeb実装。キュー、端末内保存、長文分割、PWAの設計を確認できます。生成AI音声APIは使用していません。

## AI活用と品質管理の見方

コードや調査文の生成だけでなく、問いの設定、作業分解、一次資料への追跡、検証方法、公開してよい範囲の設計を重視しています。各Repositoryのデータ・検証器・workflow・履歴から、実際に確認できる範囲を見てください。

- 機械照合の成功、制度の現行性、人手確認は別に管理します。
- 公式資料で確認できることと、実際に再現したことを分けます。
- 公開資料だけでは分からない項目や、未確認・保留の状態を残します。
- 個人プロジェクトの実装を、職務上のIT開発経験や導入効果として扱いません。

その他の公開Repositoryも継続して残しています。上記が公共・DX・AI・業務改善の観点からの主な入口です。
