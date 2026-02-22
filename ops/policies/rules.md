# 禁止事項（憲法）

## 絶対禁止
- 本番への直接変更（PRなし）
- 承認なしの外部投稿（note/X）
- 秘密情報のコード内直書き・ログ出力
- 破壊的DB操作（全消し、スキーマ破壊）

## 危険ファイル（変更時に監査必須）
- 認証関連（auth, login, session）
- 課金関連（billing, payment, subscription）
- 権限関連（role, permission, admin）
- 環境変数（.env*, config/secrets）
- DB migration ファイル

## 承認ゲート
- note/X公開 → LINE承認必須
- Phase切り替え → 人間が手動実施
