# movie_detection
ファイルの説明

1.imglab.exe・・・画像の特定部分を手動で枠線で囲むツール。開くと変更されてしまうので開かないでください。

2.image_metadata_stylesheet.xsl・・・imglabによる枠線のデータ

3.pengin.mp4・・・検出に用いる動画

4.pengin_program.ipynb・・・実行プログラムが記載されているpythonコード

5.Snapshot.png***・・・教師データとして検出に用いている写真(たくさん撮った中から厳選しました)

6.ペンギンいらない・・・教師データとして使わなかった余りの写真


実行方法

1.pengin_program.ipynbを開く

2.2つあるうちの上のコードをまず実行。detector.svmファイルが作成されてこれが検出器となる。

3.下のコードを実行すると動画が出てきて、ペンギンが枠で囲まれていることが確認できる。
