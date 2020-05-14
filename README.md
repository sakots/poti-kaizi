# POTI-board改二
phpお絵かき掲示板スクリプトPOTI-boardをさらに改良していくプロジェクトです。
  
<a href="https://github.com/funige/neo/">PaintBBS NEO</a>  
<a href="https://github.com/sakots/poti-kai/">POTI-board改</a>  
  
## 概要
POTI-board改で使用しているテンプレートエンジン「htmltemplate.inc」はphp7だとエラーが出てしまうので今後が危ない…  
ということでなんか新しいテンプレートエンジンはないか探したところ、
  
<a href="http://skinny.sx68.net/">Skinny</a>  
  
見つけました！これに移植します！ → だいたいできた～～ァ！

## 現状

- うごく！

## 今後

- 独自タグは廃止予定
- pallete.txtを読み込めないのをどうにかする
- 管理パスにpassword_hashを使えないか？

## 履歴

### [2020/05/14] v2.0.0a8

- 管理パスをグローバル定数から変数に変更(byさとぴあ)

### [2020/05/14] v2.0.0a7

- DEF_FONTCOLORの設定がないテンプレートの場合を想定

### [2020/05/14]

- 動画が再生されないの、スキンの問題でした。

### [2020/05/14] v2.0.0a6

- デフォルトスキン変更、スキンフォルダ作成 (config.php要再設定！)
- palleteの問題に暫定対処

### [2020/05/14] v2.0.0a5

- htmlの生成に成功(byさとぴあ) 大感謝。
- スキンのエラー修整。

### [2020/05/13] v2.0.0a4

- htmlは生成されないが、動く。

### [2020/05/07] v2.0.0a3

- いちからつくりなおす。
- ログが生成されるのは確認、HTML生成されず

### [2018/09/16] v2.0.0a2

- 記録

### [2018/09/15] v2.0.0a1

- プロジェクト開始
- ログが生成されるのは確認、HTML生成されず