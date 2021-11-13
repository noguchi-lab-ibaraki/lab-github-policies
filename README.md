# 組織管理ルール

## ユーザ管理

- 年度別に`noguchi-lab-<year>`という名前のチームを作成し、当年度のメンバーを追加する
- 新メンバーは`noguchi-lab-all`に追加する
- 2段階認証が必須

## 権限管理

- *Repository* のベース権限がnone
- *Repository* と *Issue* の削除が禁止されている。(Ownだけが削除できる)
- ゼミ関連の *Repository* は基本`noguchi-lab-all`に *maintain* レベルの権限を付与する
- 公開したい場合以外、*Repository* 全部 *private* にするべき
- 共同作業必要の *Repository* は 共同作業者だけをInviteする。ただし、Ownerはどの *Repository* にもフルアクセスを所持している
- *Owner* ロールの取得は申請制、自分のセキュリティ管理に自信がある方に付与する

## 卒業後

- 卒業後メンバーの *Repository* はチーム`noguchi-lab-all`に *maintain* レベル権限を付与する
- 卒業後、学生Ownerのロールはmemberまたはoutside-collaboratorに変更する

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
