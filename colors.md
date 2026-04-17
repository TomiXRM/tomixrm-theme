# カラーリファレンス

## 背景色

| 用途 | HEX |
|------|-----|
| エディタ背景 | `#2d2a2e` |
| サイドバー / タイトルバー背景 | `#221f22` |
| アクティビティバー背景 | `#19181a` |
| パネル / ホバー背景 | `#403e41` |

---

## ベースパレット

| 色名 | HEX | プレビュー用途 |
|------|-----|--------------|
| Pink / Red | `#ff6188` | キーワード、タグ名、エラー |
| Orange | `#fc9867` | 変数引数、プレースホルダー |
| Yellow | `#ffd866` | 文字列、見出し |
| Green | `#a9dc76` | 関数名、リンク、Diff追加 |
| Cyan | `#78dce8` | 型名、クラス、名前空間 |
| Purple | `#ab9df2` | 定数、数値、ラベル |
| White | `#fcfcfa` | デフォルトテキスト |
| Light Gray | `#c1c0c0` | 言語変数（self/this等） |
| Gray | `#939293` | 句読点、ブレース |
| Dark Gray | `#727072` | コメント |
| Darker Gray | `#5b595c` | 行番号、非アクティブ要素 |

---

## シンタックスカラー詳細

### コメント

| スコープ | HEX | スタイル |
|----------|-----|---------|
| コメント全般 | `#727072` | italic |
| JSDoc entity name / variable | `#c1c0c0` | — |
| Comment TODO / FIXME | `#ab9df2` | — |
| コメント開始 / 終了の句読点 | `#727072` | — |
| Docstring | `#727072` | — |

---

### 文字列 (String)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| 文字列全般 | `#ffd866` | — |
| テンプレートリテラル内ソース | `#fcfcfa` | — |
| 文字列内埋め込み句読点 | `#939293` | — |
| テンプレートリテラル `${}` 区切り | `#ff6188` | — |
| リンクタイトル文字列 | `#ff6188` | — |
| リンク説明文字列 | `#78dce8` | — |
| Regex begin / end | `#ff6188` | — |

---

### 定数 (Constant)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| 定数全般 | `#ab9df2` | — |
| `constant.other`（汎用） | `#fcfcfa` | — |
| `constant.other.placeholder` | `#fc9867` | — |
| `constant.other.symbol`（Ruby） | `#fc9867` | — |
| `constant.other.elm` | `#78dce8` | — |
| 数値 (numeric) | `#ab9df2` | — |
| 文字エスケープ | `#ab9df2` | — |

---

### キーワード (Keyword)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| キーワード全般 | `#ff6188` | — |
| 制御構文（if / while 等） | `#ff6188` | — |
| 演算子 (operator) | `#ff6188` | — |

---

### ストレージ (Storage)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| ストレージ全般 | `#ff6188` | — |
| 型宣言（int / class / func 等） | `#78dce8` | italic |
| 修飾子（static / const / public 等） | `#ff6188` | italic |
| Fat arrow (`=>`) | `#ff6188` | — |

---

### エンティティ (Entity)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| 関数名 | `#a9dc76` | — |
| クラス名 | `#78dce8` | — |
| 型名 | `#78dce8` | — |
| 名前空間 | `#78dce8` | — |
| 定数名 | `#ab9df2` | — |
| 継承クラス | `#78dce8` | italic |
| タグ名（HTML / JSX） | `#ff6188` | — |
| タグ属性名 | `#78dce8` | italic |
| セクション見出し | `#ffd866` | — |
| 演算子名 | `#ff6188` | — |

---

### 変数 (Variable)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| 変数全般 | `#fcfcfa` | — |
| 関数引数 | `#fc9867` | italic |
| 言語変数（self / this / super 等） | `#c1c0c0` | italic |
| `variable.other.constant` | `#ab9df2` | — |
| `variable.other.class` | `#78dce8` | — |
| `variable.other.enummember` | `#ab9df2` | — |
| 関数呼び出し変数 | `#a9dc76` | — |
| Ruby インスタンス変数 | `#ab9df2` | — |
| `arguments` 予約変数 | `#ab9df2` | — |

---

### サポート (Support)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| ライブラリ定数 | `#78dce8` | — |
| ライブラリ関数 | `#a9dc76` | — |
| ライブラリ型 | `#78dce8` | italic |
| ライブラリクラス | `#78dce8` | — |
| ライブラリ変数 | `#78dce8` | — |
| JSON / プロパティ名 | `#fcfcfa` | — |

---

### CSS / SCSS / LESS

| スコープ | HEX | スタイル |
|----------|-----|---------|
| CSSクラス名 | `#a9dc76` | — |
| CSS ID | `#fc9867` | — |
| CSS疑似クラス / 疑似要素 | `#78dce8` | italic |
| SCSS / LESS 変数 | `#fc9867` | italic |
| ベンダープレフィックス | `#c1c0c0` | — |

---

### Markup（Markdown / reStructuredText 等）

| スコープ | HEX | スタイル |
|----------|-----|---------|
| 見出し | `#ffd866` | — |
| リンク | `#a9dc76` | — |
| Raw / コードブロック | `#fc9867` | — |
| Bold | — | bold |
| Italic | — | italic |
| Underline | — | underline |
| Diff 追加 | `#a9dc76` | — |
| Diff 削除 | `#ff6188` | — |
| Diff 変更 | `#ffd866` | — |
| Diff 無視 / 未追跡 | `#939293` | — |

---

### 句読点 (Punctuation)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| 句読点全般 | `#939293` | — |
| ブレース / ブラケット / 区切り | `#939293` | — |
| グループ（Regex等） | `#fcfcfa` | — |
| 埋め込みブロック（`<?php`等） | `#fc9867` | — |
| テンプレートリテラル区切り | `#ff6188` | — |

---

### 無効 (Invalid)

| スコープ | HEX | スタイル |
|----------|-----|---------|
| Invalid | `#ff6188` | italic underline |
| Invalid deprecated | `#fc9867` | italic underline |

---

### Region カラー（Sublime Text互換）

| 名前 | Foreground | Background |
|------|-----------|------------|
| redish | `#ff6188` | `#ff618859` |
| orangish | `#fc9867` | `#fc986759` |
| yellowish | `#ffd866` | `#ffd86659` |
| greenish | `#a9dc76` | `#a9dc7659` |
| bluish | `#78dce8` | `#78dce859` |
| purplish | `#ab9df2` | `#ab9df259` |
| pinkish | `#ff6188` | `#ff618859` |

---

### ブラケットハイライト

| 順番 | HEX |
|------|-----|
| 1番目 | `#ff6188` |
| 2番目 | `#fc9867` |
| 3番目 | `#ffd866` |
| 4番目 | `#a9dc76` |
| 5番目 | `#78dce8` |
| 6番目 | `#ab9df2` |

---

## まとめ：色と役割の対応表

| HEX | 色名 | 主な用途 |
|-----|------|---------|
| `#2d2a2e` | Editor BG | エディタ背景 |
| `#ff6188` | Pink | キーワード・演算子・タグ名・エラー |
| `#fc9867` | Orange | 関数引数・プレースホルダー・CSS ID |
| `#ffd866` | Yellow | 文字列・Markup見出し |
| `#a9dc76` | Green | 関数名・ライブラリ関数・リンク・Diff追加 |
| `#78dce8` | Cyan | 型・クラス・名前空間・ライブラリ |
| `#ab9df2` | Purple | 定数・数値・enum |
| `#fcfcfa` | White | デフォルトテキスト・変数 |
| `#c1c0c0` | Light Gray | 言語変数（self/this）・ベンダープレフィックス |
| `#939293` | Gray | 句読点・ブレース・コメント補助 |
| `#727072` | Dark Gray | コメント本文 |
