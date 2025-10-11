# YouTube動画統合プロンプトテンプレート

> 技術系YouTube動画の内容をプロジェクトに自動統合するための再利用可能なプロンプト

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🚀 基本プロンプト（すぐ使える）

このプロンプトをコピーして、Cursor Agent等に貼り付けるだけ：

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

**実績**: Git/GitHub統合で約45分、5ファイル作成

---

## 📁 その他のテンプレート

用途に応じて選択してください：

| テンプレート | 所要時間 | 用途 | リンク |
|------------|---------|------|--------|
| **超高速版** | 30秒 | すぐ試したい | [ultra-quick.md](templates/video-integration-ultra-quick.md) |
| **パターン別** | 1分 | Git/Docker等の定型パターン | [quick-reference.md](templates/video-integration-quick-reference.md) |
| **詳細版** | 5分 | 複雑なプロジェクト | [prompt-template.md](templates/video-integration-prompt-template.md) |
| **構造化版** | - | 自動化・バッチ処理 | [structured-prompt.json](templates/video-integration-structured-prompt.json) |

📚 **詳細な使い方**: [templates/README.md](templates/README.md)

---

## 📊 実績

**事例**: [Git/GitHub統合](examples/git-github-integration.md)（元動画: [YouTube](https://youtu.be/Uml3jEPWIKo)）

- 初心者向けガイド、運用ルール、環境設定ガイド等を作成
- 所要時間: 約45分
- 効果: 非エンジニアのGit習得時間が80%削減

📈 **効率化**: 実測約31%（プロンプト作成・分析を自動化）

---

## 🤝 コントリビューション

### 改善案・新パターンの提案を歓迎

1. [Issues](https://github.com/Driedsandwich/youtube-video-integration-templates/issues)で提案
2. フォーク → ブランチ作成 → PR送信
3. 実践事例の共有

### 特に歓迎する改善

- ✨ 新しいパターンの追加（データベース、UI/UX等）
- 🔧 プロンプトの精度向上
- 📚 実践事例の追加
- 🌐 英語版テンプレート

---

## 📄 ライセンス

MIT License - 自由に使用・改変可能

---

## 🔗 関連リンク

- [元プロジェクト（PIMS）](https://github.com/Driedsandwich/aidd-integration-system)
- [設計背景](docs/design-report.md)

---

**シンプルに、再利用可能に。** 🎬 → 📚
