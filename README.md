# bedtime-routine-phone-limiter

睡眠前ルーティン・スマホ制限 は、睡眠前だけのルーティン、許可アプリ、制限ログを扱うAndroidアプリです。

## Closed Alpha Scope

- Rank: 40
- Tier / Score: P2 / 59
- Domain / Idea No: AndroidApp / 3
- 主な公開先: Google Play
- GitHub: https://github.com/Sunmax0731/bedtime-routine-phone-limiter
- Prerelease: https://github.com/Sunmax0731/bedtime-routine-phone-limiter/releases/tag/v0.1.0-alpha.1

## 実装概要

- `src/core`: 製品プロファイルと代表シナリオ評価
- `src/validators`: 期待結果検証
- `src/report`: 検証レポート生成
- `src/review-model`: レビューゲートと責務モデル
- `src/cli`: `samples/representative-suite.json` の自動検証

## 代表データ

`samples/representative-suite.json` は `happy-path`、`missing-required`、`warning`、`mixed-batch` を含みます。

## 検証

```powershell
cd D:\AI\AndroidApp\bedtime-routine-phone-limiter
cmd.exe /d /s /c npm test
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` を参照してください。
