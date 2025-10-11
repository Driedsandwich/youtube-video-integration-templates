# YouTube動画統合テンプレート

> 技術系YouTube動画の内容をプロジェクトに自動統合するための再利用可能なプロンプト集

---

## 🚀 基本プロンプト（推奨）

最もシンプルで実用的。**これだけで十分使えます。**

```markdown
@[YouTube動画URL] この動画の内容をプロジェクトに統合してください。

## 統合方針
1. 動画のトランスクリプトを取得・分析
2. プロジェクト構造を把握（docs/, .cursor/rules/, README.md）
3. TODOリストを作成
4. 以下を段階的に作成/更新:
   - 初心者向けガイド（docs/配下）
   - Cursorルール（.cursor/rules/配下）
   - 設定ファイル（.gitignore, .env.example等、必要に応じて）
   - 統合運用ガイドへのセクション追加（必要に応じて）
   - PRテンプレート改善（必要に応じて）
   - README（新規ドキュメントへのリンク）
5. 完了報告（作成ファイル、メリット、次のステップ）

## 制約
- 既存の命名規則・スタイルに従う
- 機密情報（APIキー等）を絶対に含めない
- 日本語で記述
- 既存ドキュメントとの整合性を保つ
```

**使い方**: `[YouTube動画URL]`を実際のURLに置き換えて、Cursor Agentで実行

---

## 📁 その他のテンプレート（オプション）

| ファイル | 用途 |
|---------|------|
| [ultra-quick.md](video-integration-ultra-quick.md) | パターン特化版（Git/Docker/セキュリティ） |
| [quick-reference.md](video-integration-quick-reference.md) | 5パターン+トラブルシューティング |
| [prompt-template.md](video-integration-prompt-template.md) | 完全カスタマイズ版 |
| [structured-prompt.json](video-integration-structured-prompt.json) | JSON形式・自動化 |

---

## 📊 実績

**事例**: Git/GitHub統合（[元動画](https://youtu.be/Uml3jEPWIKo)）
- 所要時間: 約45分
- 作成物: 5ファイル
- 効果: Git習得時間が80%削減

---

## 🤝 改善案・PR歓迎

- 新しいパターンの提案
- プロンプトの精度向上
- 実践事例の共有

[Issues](https://github.com/Driedsandwich/youtube-video-integration-templates/issues) / [PRを送る](https://github.com/Driedsandwich/youtube-video-integration-templates/pulls)

---

**シンプルに、再利用可能に。**
