# 組織管理ルール

- 年度別に`noguchi-lab-<year>`という名前のチームを作成し、当年度のメンバーを追加する
- *Owner* ロールの取得は申請制、自分のセキュリティ管理に自信がある方に付与する
- 2段階認証が必須
- *Repository* と *Issuse* の削除が禁止されている。
- 公開したい場合以外、*Repository* 全部 *private* にするべき
- *Repository* のベース権限がwrite
- 卒業後メンバーの *Repository* は全チームに *maintainer* レベル権限を付与する
- 共同作業必要の *Repository* は *Triage* 権限に設定し、それ以外の *Repository* は *Read* まで設定するべき

# Ownerロール　マニュアル

### *Repository* のベース権限設定

`組織のsettings -> member_privileges -> Base permissions`

### リソースの削除禁止設定
`組織のsettings -> Repository deletion and transfer/Issue deletion`

### Owner権限の付与
`組織のPeople -> Role -> Change Role -> Owner`

# Repository 権限設定　マニュアル

### チームへのアクセス設定
`リポジトリのsettings -> Manage access -> Add team(新規チームの場合) -> Role:XX から変更`
