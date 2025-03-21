# 貢献ガイドライン (Contributing Guidelines)

このリポジトリへの貢献に興味を持っていただき、ありがとうございます！
以下のガイドラインに従って貢献をお願いします。

---

## 1. Issue の作成

新しい機能提案やバグ報告を行う場合は、以下の点を記載してください。

### 🐛 バグ報告 (Bug Report)

- **発生した現象**: 具体的な問題の説明
- **再現手順**: 問題を再現する手順
- **期待する動作**: 本来の正しい挙動
- **環境情報**: OS, バージョン情報, 依存ライブラリなど

### 💡 機能提案 (Feature Request)

- **概要**: 追加したい機能の説明
- **目的**: なぜこの機能が必要か
- **実装のアイデア**: 具体的な方法があれば記載

---

## 2. プルリクエスト (Pull Request)

コードを修正する際は、以下の手順に従ってください。

### ✅ 開発の流れ

1. `main` ブランチから feature **ブランチ** を作成 (`git checkout -b feature/new-feature`)
2. コードを編集し、コミット (`git commit -m "Add new feature"`)
3. プッシュ (`git push origin feature/new-feature`)
4. PR を作成し、適切なレビュアーを指定
5. レビュー後、必要に応じて修正

### 📝 コードスタイル

- Python: `black` でフォーマット
- C++: `clang-format` で整形
- 可能な限り **テストを追加** すること

---

## 3. ラベルの使い方

Issue や PR には以下のラベルを付けてください。

| ラベル               | 用途                     |
| -------------------- | ------------------------ |
| `bug`              | バグ報告                 |
| `enhancement`      | 新機能の提案             |
| `documentation`    | ドキュメント修正         |
| `help wanted`      | 他の人の支援が必要       |
| `good first issue` | 初心者向けの簡単なタスク |

---

## 4. コミュニケーション

質問がある場合は、[Discussions](https://github.com/KCCTRobotics-OBs/KCCT-Robotics-Board/discussions) を活用してください。
