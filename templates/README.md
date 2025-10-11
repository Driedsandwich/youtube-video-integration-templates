# 動画統合テンプレート集

> YouTube動画の内容をプロジェクトに統合するための標準プロンプト・テンプレート

## 📚 概要

技術系YouTube動画から得られる知見を、プロジェクトに体系的に統合するためのテンプレート集です。AI Agent（Cursor等）に渡すことで、自動的にドキュメント作成・ルール追加・設定ファイル更新を実施できます。

---

## 🎯 使用シーン

### こんな時に使える

- ✅ 技術入門動画の内容をプロジェクトに取り込みたい
- ✅ ベストプラクティスをチーム全体に浸透させたい
- ✅ 非エンジニアメンバー向けのガイドを作りたい
- ✅ AI駆動開発のルールを強化したい
- ✅ セキュリティ・CI/CD等の運用を標準化したい

---

## 📁 テンプレート一覧

### 1. 詳細版テンプレート（推奨）

**ファイル**: [`video-integration-prompt-template.md`](./video-integration-prompt-template.md)

**用途**: 初回統合、複雑なプロジェクト、詳細な制約がある場合

### 2. 超高速テンプレート（最速）

**ファイル**: [`video-integration-ultra-quick.md`](./video-integration-ultra-quick.md)

**用途**: 30秒で即実行、最小限の設定

### 3. パターン別テンプレート

**ファイル**: [`video-integration-quick-reference.md`](./video-integration-quick-reference.md)

**用途**: 用途別の最適化されたテンプレート

### 4. 構造化プロンプト（上級者向け）

**ファイル**: [`video-integration-structured-prompt.json`](./video-integration-structured-prompt.json)

**用途**: バッチ処理、CI/CD統合、プログラマティックな操作

---

## 🚀 クイックスタート

```markdown
@[動画URL] この動画の内容をプロジェクトに統合してください。

以下の手順で進めてください：
1. トランスクリプトを取得して内容を分析
2. プロジェクト構造を把握
3. TODOリストを作成して段階的に実装
4. ガイド、ルール、設定ファイル、READMEを作成/更新
5. 完了報告
```

---

## 📊 実績データ

### Git/GitHub統合の事例

**元動画**: [非エンジニアのためのGit+GitHub入門](https://youtu.be/Uml3jEPWIKo)

**効果**:
- 非エンジニアメンバーのGit習得時間が80%削減
- APIキー漏洩リスクをルール化で防止
- チーム全体でブランチ戦略が統一

---

**AI駆動開発の知見を、プロジェクトの資産に。**
