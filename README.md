 # 組織管理ルール
- 年度別に`noguchi-lab-<year>`という名前のチームを作成し、当年度のメンバーを追加する
- 新メンバーは`noguchi-lab-all`に追加する
- *Owner* ロールの取得は申請制、自分のセキュリティ管理に自信がある方に付与する
- 2段階認証が必須
- *Repository* と *Issuse* の削除が禁止されている。
- 公開したい場合以外、*Repository* 全部 *private* にするべき
- *Repository* のベース権限がnone
- 卒業後メンバーの *Repository* はチーム`noguchi-lab-all`に *maintainer* レベル権限を付与する
- ゼミ関連の *Repository* は基本`noguchi-lab-all`に *maintainer* レベルの権限を付与する
- 共同作業必要の *Repository* は 共同作業者だけをInviteする。ただし、Ownerはどの *Repository* にもフルアクセスを所持している

# マニュアル

### *Repository* のベース権限設定

`組織のsettings -> member_privileges -> Base permissions`

### リソースの削除禁止設定
`組織のsettings -> Repository deletion and transfer/Issue deletion`

### Owner権限の付与
`組織のPeople -> Role -> Change Role -> Owner`

### チームへのアクセス設定
`リポジトリのsettings -> Manage access -> Add team(新規チームの場合) -> Role:XX から変更`

### 個別ユーザのアクセス設定
`リポジトリのsettings -> Manage access -> Add people -> Role:XX 変更`
