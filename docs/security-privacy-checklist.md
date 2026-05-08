# Security / Privacy Checklist

        ## 方針

        Usage Access は任意の手動許可とし、閲覧履歴や内容は保存しない

        ## チェック

        - [x] 外部送信をMVP外にした。
        - [x] サンプルに実個人情報を含めない。
        - [x] 手動テストで確認すべき権限を列挙。
        - [x] release asset に手動テスト手順を添付。

        ## Android / Host 権限

        - PACKAGE_USAGE_STATS は任意
- POST_NOTIFICATIONS は任意
- AccessibilityService は閉域アルファでは未使用

        ## Adobe 公式参照

        - 対象ドメイン docs と created_idea metadata を優先。
