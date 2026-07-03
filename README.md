# 浜名湖鰻 — 湖と炭火の記録

浜名湖うなぎを紹介する読み物風の1ページサイトです。汽水湖としての成り立ち、日本の養鰻発祥の歴史、浜名湖の鰻が特別とされる理由、白焼き・蒲焼の違い、土用の丑の日、名物「うなぎパイ」まで、史実に基づいて構成しています。

## 概要

- **公開URL**: https://katzkawai.github.io/hamanako-unagi/
- **構成**: `index.html` 1枚に完結した静的サイト（CSS・JSはインライン、外部リクエストなし）
- **フォント**: 見出し用「Zen Old Mincho」、本文用「Zen Kaku Gothic New」を実際に使用する文字だけにサブセット化し、WOFF2をBase64でHTMLに直接埋め込み
- **演出**: ヒーロー部の炭の熾火アニメーション（Canvas、`prefers-reduced-motion` 対応）、スクロール連動のセクション表示

## 更新履歴

### 2026-07-04
- 浜名湖うなぎ紹介サイトを構築し、初版を公開
- GitHubリポジトリ `katzkawai/hamanako-unagi` を作成しリモートへプッシュ
- GitHub Pagesとして公開
- README.mdを追加

## 使用LLM

本サイトの企画・調査・実装は [Claude Sonnet 5](https://www.anthropic.com/claude)（Anthropic）を、[Claude Code](https://claude.com/claude-code) 経由で使用して行いました。
