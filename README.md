<!--
Program Name: SCAO Learning Hub README
Language: Markdown
Function: SCAO Learning全体の入口。概要・開始位置・主要Repository・詳細文書への導線を示す。
Created: 2026-08-24
Last Updated: 2026-08-24
Author: Takashi Oikawa
AI: Cursor Grok 4.6
Memo: Hub入口。詳細は docs/ および各学習Repositoryを正本とする。
-->

# SCAO Learning Hub

SCAO Learningの入口です。教材本体ではありません。

このHubは、SCAOの存在意義を伝え、学習の全体像を示し、適切な学習Repositoryへ案内します。

## SCAOとは

**SCAO（SPEC-Core Architecture - O）** は、初心者が目的や完成地点を見失わず、AIを活用したソフトウェア開発（ポートフォリオ制作）を進めるための**選択肢の一つ**です。

唯一の正解でも、必須の方法でも、完成された万能な開発方法論でもありません。考え方の詳細は [docs/SCAO_CONCEPT.md](docs/SCAO_CONCEPT.md) を参照してください。

## 誰のためのものか / 何のためにあるのか

未経験からIT系職種を目指す人など、限られた訓練期間のなかで学習とポートフォリオ完成を両立したい人のための入口です。

実装から始めるとGoalを失いやすい、という問題に対し、目的・要求・完成条件を先に整理し、AIを学習・開発の支援者として使う考え方を案内します。

## SCAO Learning全体図

```text
SCAO Learning Hub（入口・学習体系）
    │
    ├─ SCAOの考え方 ………… docs/SCAO_CONCEPT.md
    ├─ 学習の順序 …………… docs/LEARNING_FLOW.md
    └─ 教材・Repository案内 … docs/LEARNING_RESOURCES.md
            │
            ├─ ai-setup-materials
            │     AI学習環境（Persona・設定の正本）
            │
            └─ scao-learning-kit（未完成）
                  学習教材の正本
```

学習の順序（概要）:

```text
Orientation（考え方を知る）
    ↓
Level 0（AI学習環境を準備する）
    ↓
Level 1（目的・要求・完成条件を決める）
    ↓
Level 2（要件・簡易設計を考える）
    ↓
Level 3（AIを活用して実装・検証する）
    ↓
Level 4（役割分担・レビューを理解する）
```

順番は固定ではありません。不足や問題が出たら、教材またはAI環境を見直して戻ります。詳細は [docs/LEARNING_FLOW.md](docs/LEARNING_FLOW.md) を参照してください。

## 学習開始位置

1. このREADMEで全体像を把握する
2. 必要なら [SCAOの考え方](docs/SCAO_CONCEPT.md) を読む
3. [学習の順序](docs/LEARNING_FLOW.md) に沿って、まず **Level 0** でAI学習環境を準備する  
   → [`ai-setup-materials`](https://github.com/t-oikawa-sendai/ai-setup-materials)
4. 教材が必要になったら [`scao-learning-kit`（未完成）](https://github.com/t-oikawa-sendai/scao-learning-kit) を参照する

最初から詳細理論を覚え込む必要はありません。Goalと完成地点を見失わないこと、AIを丸投げせず支援者として使うことが先です。

## 主要Repository

| Repository | 役割 | 状態 |
|---|---|---|
| [`ai-setup-materials`](https://github.com/t-oikawa-sendai/ai-setup-materials) | AI学習環境（Persona・設定） | Persona・設定の正本 |
| [`scao-learning-kit`（未完成）](https://github.com/t-oikawa-sendai/scao-learning-kit) | 学習教材 | **未完成**。完成済みと誤認しないこと |

各Repositoryの役割と注意事項は [docs/LEARNING_RESOURCES.md](docs/LEARNING_RESOURCES.md) を参照してください。

## 詳細文書

- [SCAOの考え方を詳しく知りたい](docs/SCAO_CONCEPT.md)
- [学習の順序を知りたい](docs/LEARNING_FLOW.md)
- [教材やAI設定Repositoryを探したい](docs/LEARNING_RESOURCES.md)

## 注意事項

- SCAOは選択肢の一つであり、組織やプロジェクトで指定された手順がある場合はそちらを優先してください。
- `scao-learning-kit` は未完成です。存在しない教材を完成済みとして扱わないでください。
- 秘密情報・個人情報を、AIへ不用意に入力しないでください。
- AIの回答を、自動的に正解として扱わないでください。最終判断は利用者自身が行います。
