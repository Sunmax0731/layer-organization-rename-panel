# レイヤー整理・命名修復パネル

layer-organization-rename-panel は PhotoshopでPSD納品、商品画像、UI素材を作る制作者 向けの closed alpha プロダクトです。レイヤー名、グループ、ロック状態、修復案を一覧化し、納品前の命名崩れを直す。

## Source

- PICKUP Rank: 50
- Domain / Idea No: AdobePlugin / 2
- Repository: layer-organization-rename-panel
- 主な公開先: BOOTH / GitHub Release
- created_idea: `D:/AI/AdobePlugin/created_idea_002_layer-organization-rename-panel`
- 同梱ZIP: `D:/AI/AdobePlugin/created_idea_002_layer-organization-rename-panel/idea_002_layer-organization-rename-panel.zip`
- 開始時 README: 存在しない
- Adobe host: Photoshop
- Host inference: レイヤー整理と命名修復はPSD制作中のPhotoshopレイヤーパネル操作に最も近いため。

## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- src/adobe/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/layer-organization-rename-panel-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

