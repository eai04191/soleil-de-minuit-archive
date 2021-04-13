# **soleil de minuit アルバム特設サイト** アーカイブ

![アルバムジャケット](./img/cd_information_1/img_cd_inforation_1_cd_jacket_2.png)

このリポジトリは過去に `http://qulalimstella.com/sp/soleil_de_minuit/` の URL で公開されていた **soleil de minuit アルバム特設サイト** を internet archive や archive.today に残っていた断片から復旧したものです。

## オリジナルウェブサイトデザイン

[かめのこわたし](http://kamenokowatashi.com/)

### 権利者の方へ

問題がある場合は GitHub の Issue か、メール `eai@mizle.net` までご連絡ください。24 時間以内に対応させていただきます。

## オリジナルからの変更点

-   画像, css, js のリンク先の変更
-   ライブラリのリンク先を cdnjs, jsdelivr に変更
-   Google Fonts を css v2 に変更
-   SoundCloud の embed 先の変更
    -   リンク先が不明だったので Sennzai さんのものを使用しました
-   loading 処理
    -   wayback machine の仕様でインラインスクリプトが削除されていたため、ページ読み込み完了時に loading 要素をフェードアウトさせる処理を追加しました。
    -   本来はロゴが出るようになっていたと思われるのですが、当時の挙動がわからないためフェードアウトするだけにしてあります。
    -   ついでに読み込み中にスクロール出来ないようにしてあります
