# インストールガイド

## Closed Alpha Package

1. GitHub Release `v0.1.0-alpha.1` から assets を取得する。
2. `dist/layer-organization-rename-panel-docs.zip` を展開して README と manual-test を確認する。
3. repo を clone する場合:

```powershell
git clone https://github.com/Sunmax0731/layer-organization-rename-panel.git
cd layer-organization-rename-panel
npm test
```

## Host Setup

1. 作業ディレクトリ `D:\AI\AdobePlugin\Photoshop\layer-organization-rename-panel` で `npm test` を実行します。
2. 対象ホストは `Photoshop` です。推定根拠は README と `docs/source-idea-pack.json` を参照します。
3. Adobe UXP Developer Tool または対象ホストのスクリプト読み込み機能で `src/adobe` を読み込みます。
4. パネルまたはスクリプトの検品結果がサンプルと同じ分類になることを確認します。

