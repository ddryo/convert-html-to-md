# HTML → Markdown 変換ツール

HTML を Markdown に変換するシンプルな Web ツールです。

## 機能

- HTML を Markdown 形式に変換
- `span` / `div` タグを除去して構造だけを残す
- `pre` → コードブロック（\`\`\`）、`code` / `strong` などのタグを適切に変換
- リアルタイムで変換結果を確認
- Markdown をクリップボードにコピー

## 使い方

1. `index.html` をブラウザで開く
2. 左側のテキストエリアに HTML を貼り付ける
3. 「変換する」ボタンをクリック
4. 右側に Markdown 形式で変換結果が表示される
5. 「Markdown をコピー」ボタンでクリップボードにコピー

## 対応している HTML タグ

- 見出し（h1-h6）
- 段落（p）
- 太字（b, strong）
- 斜体（i, em）
- インラインコード（code）
- コードブロック（pre）
- 箇条書き（ul, ol, li）
- リンク（a）
- 画像（img）
- 水平線（hr）
- 改行（br）

## ライセンス

MIT License
