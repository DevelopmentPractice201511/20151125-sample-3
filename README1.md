#・　vimとは
vimは編集機能だけに注力したテキストエディタです。

<img src="http://www.kaoriya.net/blog/2013/12/06/vimlogo-564x564.png" width="300">

#・　vimの特徴
- マルチプラネットフォーム
 
- 軽くて速い
 
- マウスがいらない
 
#・　vim５箇条
- チュートリアルをやる
 
- :helpを使う事を覚える

- カーソルキー（矢印）を押さない
 
- 有名Vimmerを知る
 
- Vimのコミュニティ
 

#・　よく使われるコマンド
##　 ファイル操作
- :w　　上書き保存
- :q　　編集終了
- :q! 　強制的に終了（編集されていても保存確認せず終了）
- :wq 　保存して終了

- :e [file-name]　　ファイルをコマンドで指定して編集
- :E　　vim上でファイルリストを開いてファイルを指定し、編集作業
- :bd　　カレントのバッファーを閉じる
- :bn　　次のバッファーに移る
- :bp　　前のバッファーに移る
 
##    標準モード時
### 　カーソル移動  
- j　　上へ（カーソル移動）
- k　　下へ（カーソル移動）
- h　　左へ（カーソル移動）
- l　　右へ（カーソル移動）

### 　ヤンク(コピー)
- x　　カーソル位置の文字を消去
- yy　　その行をヤンク
- dd　　その行を削除する
- y[num]　　num行分ヤンクする
- d[num]　　num行分削除する
- y[num]　　num行分ヤンクする
- d[num]　　num行分削除する
- y0　　カーソル位置からその行の先頭まで
- d0　　カーソル位置からその行の先頭まで
- y$　　カーソル位置からその行の終わりまで
- d$　　カーソル位置からその行の終わりまで
- yw　　カーソル位置の単語をヤンク
- yW　　カーソル位置の単語をヤンク（:や%などを含む）
- ye　　カーソル位置から単語末尾までをヤンク（空白はヤンクしない）

- p　　ヤンク、削除したものをカーソルの次の行（or次の位置）に貼り付ける
- P　　ヤンク、削除したものをカーソルの前の行（or前の位置）に貼り付ける
 
### 　やり直しコマンド
- u　　最後にやったコマンドを取り消す（undo）
- U　　行全体の変更に対する取り消し（U を取り消すのは u）
- CTRL-R　　取り消しの取り消し（redo）

##    挿入モード時
###　 コマンド	動作
- x　　カーソル位置の文字を消す（del）
- X　　カーソル位置の前の文字を消す（backspace）
- i　　カーソル位置から挿入モードに入る
- I　　カーソルのある行の文頭から挿入モードに入る
- a　　カーソル位置の1つ後から挿入モードに入る
- A　　カーソルのある行の末尾から挿入モードに入る
- o　　カーソル行の下の行に新しく行を追加し挿入モード
- O　　カーソル行の上の行に新しく行を追加し挿入モード
- ESC	挿入モードからノーマルモードへ

#・　ＤＥＭＯ
*参考サイト*<br>[http://monmon.hateblo.jp/entry/20100122/1264142075](http://monmon.hateblo.jp/entry/20100122/1264142075)
