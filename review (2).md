修正内容をまとめたマークダウン形式のファイルを添付しますので、添付ファイルをダウンロードし、エディタで開いて修正内容を確認してください！
修正指示に対して、 *どのように修正したか* を確認したいので修正指示のすぐ下に直接 *修正内容を書き込み* 、再レビュー依頼の時に `review.md` ファイルを併せて添付してください！
マークダウンについて詳しく知りたい方は[こちら](https://giztech.gizumo-inc.work/lesson/40)にまとめてありますので読んでみてください。
以上、よろしくお願いします！

## Bolt
--- 例 ---
1. 修正指示を記載します(メンター)
   - 修正内容を記載してください(研修生)
     例) 〇〇クラスに××を指定して△△になるようにしました。
----------

## 全体

1. baseのフォントはLatoです！Ralewayはタイトルにつけてください

    .base_fontにfont-family: 'Lato' , sans-serif;を
    追加し、タイトル部分にfont-family: 'Raleway' , sans-serif;を追加しました。

2. cssの書き方ですが、cssとcssの間は1行開けましょう

    全てのCSSとCSSの間に改行を入れました。

3. 今回heightを使うところはありませんので、あるところは使わず実現しましょう

    .main_what.img-iphone.sns-box:hover のheightを削除しました。
    .latest-emailのheightを削除し、align-items: flex-start;を追加しました。

## header

1. paddingの取り方がおかしいです！アイコンの領域を広げるのではなくheaderの領域を広げましょう！

    .headerにpaddingを設定しました。

2. z-indexは999くらいにしましょう。小さいと超えられてしまいますね！

    .headerのz-indexを999にしました。

3. fasは既存クラスです

    cssのfasを消去しました。
    
## OUR LATEST WORK

1. .img-sizに大きさの指定は必要ありません。300*3+200で1100pxになるようになってます

      .img-sizを削除しました。

