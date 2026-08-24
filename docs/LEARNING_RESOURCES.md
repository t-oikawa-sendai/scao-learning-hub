<!--
Program Name: LEARNING_RESOURCES
Language: Markdown
Function: SCAO Learningで利用するRepositoryの役割と注意事項を案内する。
Created: 2026-08-24
Last Updated: 2026-08-24
Author: Takashi Oikawa
AI: Cursor Grok 4.6
Memo: Repository案内の正本。学習体系はHub、教材詳細はkit、Persona詳細はai-setup-materials。
-->

# 教材とRepository案内

[README.md](../README.md) へ戻る

この文書は、利用できるRepositoryと、それぞれの役割・注意事項を説明します。学習の順序は [LEARNING_FLOW.md](LEARNING_FLOW.md)、SCAOの考え方は [SCAO_CONCEPT.md](SCAO_CONCEPT.md) を参照してください。

情報の正本は次のとおり分けます。Hubから他Repositoryの詳細をコピーしません。

```text
scao-learning-hub
→ 学習体系・導線

scao-learning-kit（未完成）
→ 学習教材

ai-setup-materials
→ Persona・AI設定
```

## SCAO Learning Kit（未完成）

Repository: [`scao-learning-kit`（未完成）](https://github.com/t-oikawa-sendai/scao-learning-kit)

**SCAO Learning Kit（未完成）** は、学習教材を管理するRepositoryです。完成済みと誤認しないでください。個別資料の有無と本文は、必ず当該Repositoryを正本として確認してください。

扱う学習領域の例は次のとおりです。存在しない資料を完成済み教材として扱ってはいけません。

- 生成AI利用の基本
- AIへの指示
- Context
- LITM
- AIの迎合・誤り
- 要求
- 要件
- 設計
- 設計ドキュメント
- ポートフォリオ制作
- その他、現在Repositoryに存在する学習資料

2026-08-24時点の実態では、生成AI利用の基本および要求・要件・設計ドキュメント関連の資料はDraftとして存在します。ポートフォリオ制作ガイドは準備中です。最新の一覧は [`scao-learning-kit` のREADME](https://github.com/t-oikawa-sendai/scao-learning-kit) を正本とします。

### 設計ドキュメントテンプレートの注意事項

SCAO Learning Kitには、初心者向けの設計ドキュメントテンプレートがあります。

しかし目的は、**一般的な設計書の標準フォーマットを定義することではありません。**

初心者は「設計書を作成してください」と言われても、次が分からない場合があります。

- 何を考えればよいのか
- 何を書けばよいのか
- どの程度まで書けばよいのか
- どの順番で考えればよいのか

その迷いを整理するための**学習用テンプレート**として提供しています。

> このテンプレートは、ソフトウェア開発で一般的に使用される設計書の標準フォーマットを示すものではありません。

実際の設計書は、組織、プロジェクト、開発手法、システム規模、対象システムなどによって異なります。組織・プロジェクトで指定された設計書が存在する場合は、そちらを優先してください。

## ai-setup-materials

Repository: [`ai-setup-materials`](https://github.com/t-oikawa-sendai/ai-setup-materials)

AI学習環境を準備するためのRepositoryです。Persona本文と設定手順の正本は、こちらです。Hubへ転載しません。

基本Persona:

- Researcher（調査担当）
- Solution Partner（設計パートナー）
- Code Generator（コード生成担当）
- Reviewer（レビュー担当）

追加:

- Researcher Deep Research（詳細調査用）

Persona本文と設定手順は転載しません。正本は [`ai-setup-materials`](https://github.com/t-oikawa-sendai/ai-setup-materials) です。Level 0での扱い（必須ではないこと）は [LEARNING_FLOW.md](LEARNING_FLOW.md) を参照してください。
