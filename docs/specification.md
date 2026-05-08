# 仕様

        ## 対象レコード

        - `routine`
- `allowedApp`
- `limitWindow`
- `windDownAction`

        ## 必須項目

        `title`, `limitWindow`, `nextAction`

        ## 警告項目

        `permissionReason`, `reviewDate`

        ## フロー

        1. 入力レコードを受け取る。
        2. `src/core/scenarioEngine.js` が必須項目と警告項目を評価する。
        3. `src/report/reportBuilder.js` が検証結果を集計する。
        4. `dist/validation-result.json` を release evidence の前提証跡にする。

        ## 保存方針

        Usage Access は任意の手動許可とし、閲覧履歴や内容は保存しない
