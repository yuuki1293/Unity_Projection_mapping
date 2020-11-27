# -Unity-

## TeraTeamをインストールする

デフォルトのパス `C:\Program Files (x86)\teraterm\ttpmacro.exe`  
パスが違ったら start_teraterm.cs 内の FileName を変更する  
ttermpro.exe ではなく ttpmacro.exe のほう  
  
## ビルド

OneDriveの中に配置しないようにする  

## 実行

TeraTeamは閉じた状態で実行する  
必ず11で終了する  

## 信号

|送る文字列|アクション|
|:-:|:-:|
|00|光っているのを止める|
|01|一番の工具を選択|
|02|二番の工具を選択|
|03|三番の工具を選択|
|04|四番の工具を選択|
|05|五番の工具を選択|
|06|動画以外の装飾を消す|
|07|動画以外の装飾を表示|
|08|動画を赤に切り替え|
|09|動画を青に切り替え|
|10|動画を黄に切り替え|
|11|終了|
|12|次回確定で777が出る|
|13|ルーレットを回す|
