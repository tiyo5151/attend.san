# attend.san

これは意欲的な大学への登校をサポートするキャラクター育成ゲームです

#### 技術スタック

- Nextjs
- Typescript
- Clerk
- Supbase
- Prisma

## 初期設定

    npm i

### Supabase

プロジェクトの作成と DataBaseUrl の取得（session mode の url）
＊プロジェクト作成時のデータベースパスワードは記号を使うとマイグレーションが出来なくなるので、注意

### Prima

.env 作成

.env ファイルに Supabase の url を記述する

後は、テーブルを定義して、マイグレートする。

### Clerk

公式ドキュメントを参照。
https://clerk.com/docs/quickstarts/nextjs
