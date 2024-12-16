# ①課題番号-プロダクト名
家族の本棚共有アプリ

https://drive.google.com/file/d/1WaTw_uZ6_uBY3QepwdUvbFyw6hZ8Na89/view?usp=drive_link

## ②課題内容（どんな作品か）
- 購入した本を登録しておけます
- 自分以外の家族が購入した本も参照できます
- Google Books API と、Firebase Authentication を利用しました。


## ③工夫した点・こだわった点
- ログイン時に付与されるUserId をFirestore 側でも利用し、ログイン中のユーザーと本棚の情報を紐づけました。※currentUser を使うと、ログインしているユーザー情報を取得できる!!
- userId とは別に、FamiluId を付与することで、自分以外の購入本も参照できるようにしました
- 検索した本の詳細情報は、モーダル画面に表示されるようにしました（関数を再利用して、画面表示されている登録済みの本もクリック時にモーダルを表示をさせたかったのですが、タイムオーバーでした涙）


## ④難しかった点・次回トライしたいこと(又は機能)
- ユーザー認証の部分は理解が追い付いていないので、学長の動画をこのあと視聴したいと思います。
  


## ⑤質問・疑問・感想、シェアしたいこと等なんでも
- 良きタイミングでGithub にコードをアップロードしながら作業を行いました。習慣化したいです。
- 今までほぼやっていませんでしたが、他の方が書いたコードを見るのはとても勉強になるなと実感しました。
- Firestore Database 内にインデックスが作成されたのですが、これが何なのか理解ができていないです… (コンソールでエラー画面とURL が表示され、URL に飛ぶとインデックスを追加画面に誘導される)


