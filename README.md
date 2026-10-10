# ai_shain-demo

AI社員キットの試用デモ（静的サイト・ビルドなし）。

- `index.html` — 1枚ページ（スタイル・描画スクリプト込み）
- `data.js` — シナリオデータ。`SCENARIOS` 配列（正本は私有リポ `products/012-hire-today/deliverable/demo/scenario-*.json` から生成）

更新手順: 正本JSONを編集 → `python3` で `SCENARIOS` 配列として `data.js` を再生成 → commit。

CTA（商品ページへのリンク）は1本のみ。登録フォーム・個人情報の取得なし。
