### 練習したコマンド

```console
// ホームディレクトリの確認
$ pwd
// ディレクトリの確認
$ ls
// change directory
$ cd ../
// コマンドの説明
$ man ls
$ ls -la
// hオプションファイルサイズの単位を読みやすい形式で表示する
$ ls -lh
// ディレクトリ作成
$ mkdir
$ echo "happy"
"happy"
$ echo "happy 読書会" > test.txt
// 結合して表示している？
$ cat test.txt
happy 読書会
// タブをいれる
$ echo -e "hanpy\n読書会"
hanpy
読書会
$ echo -e "hanpy\n読書会\nhanpy\n読書会\nhanpy\n読書会" > test.txt
// 中身を見る別バージョン
$ less test.txt
// 上から・下からで行数を指定できる
$ head -n 3 test.txt
$ tail -n 3 test.txt
// テキストの移動
$ mv 移動させるファイル 移動先
// 削除
$ rm 削除させるファイル
// 空ファイルの作成
$ touch test2.txt
// まとめて複数を消す(絶対にrm *はやったらだめ)
$ rm *.txt
// wc ファイルの行数，単語数，バイト数を表示。単語数は一番長いところを出してる？
//「time」は指定したコマンドの実行時間と、実行時のシステムリソース情報など計測して表示するコマンド
$ time wc ~~.tsv
```
  
他、大きなファイルの分割方法等やった。