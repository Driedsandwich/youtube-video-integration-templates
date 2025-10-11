# YouTube動画統合テンプレート集

> AI駆動開発向け - 技術系YouTube動画の内容をプロジェクトに体系的に統合するための標準プロンプト集

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/Driedsandwich/youtube-video-integration-templates)](https://github.com/Driedsandwich/youtube-video-integration-templates/stargazers)

---

## 🎯 これは何？

技術系YouTube動画の内容を、**AI Agent（Cursor等）を使って自動的にプロジェクトに統合する**ためのテンプレート集です。

### できること

- ✨ **動画URLを入れるだけ** - 初心者向けガイド、実装ルール、設定ファイルを自動生成
- ⚡ **約48%の効率化** - 手動作業65分 → テンプレート使用33分
- 📚 **5つのパターン** - Git/Docker/テスト/セキュリティ/フレームワーク
- 🔧 **3段階の複雑度** - 30秒版/1分版/5分版から選択

---

## 🚀 クイックスタート（30秒）

### 1. テンプレートをコピー

```markdown
@[動画URL] この動画の内容をプロジェクトに統合してください。

以下の手順で進めてください：
1. トランスクリプトを取得して内容を分析
2. プロジェクト構造を把握（docs/, .cursor/rules/, README.md）
3. TODOリストを作成して段階的に実装
4. 以下を作成/更新:
   - 初心者向けガイド（docs/配下）
   - Cursorルール（.cursor/rules/配下）
   - 設定ファイル（.gitignore等）
   - README（新規ドキュメントへのリンク）
5. 完了報告
```

### 2. Cursor Agentに貼り付けて実行

動画URLを入れて、Cursor Composer/Agentで実行するだけ！

---

## 📁 テンプレート一覧

### 1. 詳細版テンプレート（推奨）

**ファイル**: [templates/video-integration-prompt-template.md](templates/video-integration-prompt-template.md)

**用途**: 初回統合、複雑なプロジェクト、詳細な制約がある場合

**特徴**:
- プロジェクト情報を詳細に指定
- カスタマイズガイド付き
- 約3,500語の包括的テンプレート

---

### 2. クイックリファレンス（最速）

**ファイル**: [templates/video-integration-quick-reference.md](templates/video-integration-quick-reference.md)

**用途**: すぐに結果が欲しい、定型パターンの繰り返し

**特徴**:
- 1分でコピペ実行
- 5つのパターン収録（Git/Docker/テスト/セキュリティ/フレームワーク）
- トラブルシューティング充実

---

### 3. 構造化プロンプト（上級者向け）

**ファイル**: [templates/video-integration-structured-prompt.json](templates/video-integration-structured-prompt.json)

**用途**: バッチ処理、CI/CD統合、プログラマティックな操作

**特徴**:
- JSON Schema形式
- 機械可読
- バリデーション可能

---

## 📊 実績データ

### Git/GitHub統合の事例

**元動画**: [非エンジニアのためのGit+GitHub入門](https://youtu.be/Uml3jEPWIKo)

**作成物**:
- 初心者向けガイド（約5,000語）
- Git運用ルール（約2,000語）
- 環境変数設定ガイド（約3,000語）
- PRテンプレート改善

**所要時間**: 約45分（AI Agent使用）

**効果**:
- ✅ 非エンジニアのGit習得時間が**80%削減**
- ✅ APIキー漏洩リスクを**ルール化で防止**
- ✅ チーム全体でブランチ戦略が**統一**

---

## 🎨 パターン別使用例

### Git/GitHub系

```markdown
@[動画URL] このGit/GitHub動画の内容を統合してください。

## 目的
安全なバージョン管理とAI駆動開発の統合

## 成果物
- [ ] 初心者向けガイド（GitHub Desktop使用推奨）
- [ ] Git運用ルール（.cursor/rules/git-workflow.mdc）
- [ ] .gitignoreの改善（機密情報除外）
- [ ] PRテンプレート改善
```

### Docker系

```markdown
@[動画URL] このDocker動画の内容を統合してください。

## 目的
開発環境の統一とセットアップの簡素化

## 成果物
- [ ] Docker初心者ガイド
- [ ] Dockerfile作成
- [ ] docker-compose.yml作成
```

[その他のパターンを見る →](templates/video-integration-quick-reference.md)

---

## 📈 効率化の実績

| 項目 | 手動作業 | テンプレート使用 | 削減率 |
|------|---------|----------------|--------|
| プロンプト作成 | 10分 | 1-2分 | **80-90%** |
| プロジェクト分析 | 10分 | 自動 | **100%** |
| タスク計画 | 5分 | 自動 | **100%** |
| 実装 | 30分 | 30分 | 0% |
| 統合・リンク | 10分 | 自動 | **100%** |
| **合計** | **65分** | **33-34分** | **約48%** |

---

## 🔧 カスタマイズ

### プロジェクトタイプ別

- **Webアプリケーション**: フロントエンド/バックエンド分離、デプロイ手順
- **CLIツール**: インストール手順、使用例
- **ライブラリ/SDK**: API仕様書、サンプルコード

### 対象者別

- **非エンジニア向け**: コマンド不要、図解多用、用語集
- **上級者向け**: 詳細仕様、エッジケース、最適化
- **チーム開発向け**: レビュープロセス、ブランチ戦略

---

## 📚 ドキュメント

- **[テンプレート集README](templates/)** - 詳細な使い方
- **[設計報告書](docs/design-report.md)** - テンプレート化の設計思想
- **[実績事例](examples/)** - Git/GitHub統合の実例

---

## 💡 使い方の詳細

### ステップ1: テンプレート選択

- **初回**: [詳細版テンプレート](templates/video-integration-prompt-template.md)
- **2回目以降**: [クイックリファレンス](templates/video-integration-quick-reference.md)
- **自動化**: [構造化プロンプト](templates/video-integration-structured-prompt.json)

### ステップ2: 変数置き換え

```markdown
[動画URL] → https://youtu.be/xxxxx
[プロジェクト名] → あなたのプロジェクト名
[主要技術] → Python, Node.js 等
```

### ステップ3: AI Agentで実行

- Cursor Composer/Agent機能を開く
- プロンプトを貼り付け
- 実行 → 完了報告を確認

---

## 🚨 注意事項

### トランスクリプトが必要

- YouTube動画に字幕が必須
- 字幕がない場合は、概要欄やコメントから要点を抽出

### AI生成コードのレビュー

- **必ずレビュー**してください
- 特にセキュリティ関連（APIキー等）は慎重に

### プロジェクト固有の調整

- 命名規則、ディレクトリ構成は要調整
- 既存ドキュメントとの整合性を確認

---

## 🤝 コントリビューション

### フィードバック歓迎

- 新しいパターンの提案
- テンプレートの改善案
- 実践事例の共有

### プルリクエスト

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-pattern`)
3. 変更をコミット (`git commit -m 'Add amazing pattern'`)
4. ブランチにプッシュ (`git push origin feature/amazing-pattern`)
5. プルリクエストを作成

---

## 📄 ライセンス

MIT License - 詳細は [LICENSE](LICENSE) を参照

---

## 🙏 謝辞

- **元動画**: [非エンジニアのためのGit+GitHub入門](https://youtu.be/Uml3jEPWIKo) - 数理の弾丸⚡️京大博士のAI解説
- **Cursor** - AI駆動開発エディタ
- **GitHub** - コード管理プラットフォーム

---

## 🔗 関連リンク

- **元プロジェクト**: [PIMS - Product Integration Management System](https://github.com/Driedsandwich/aidd-integration-system)
- **Issues**: [質問・フィードバックはこちら](https://github.com/Driedsandwich/youtube-video-integration-templates/issues)
- **Discussions**: [実践事例の共有](https://github.com/Driedsandwich/youtube-video-integration-templates/discussions)

---

**技術動画の知見を、プロジェクトの資産に。** 🎬 → 📚 → 🚀
