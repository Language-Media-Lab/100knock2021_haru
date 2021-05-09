# 言語処理100本ノック 2021年度
言語メディア研2021年度新入生向け勉強会として、言語処理100本ノックに取り組みます。  
教材URL: https://nlp100.github.io/ja/  

毎週全員1章分（10問）解いてください。(※ただし2章は除く)  
勉強会のときに毎週1人1章分、自分のコードを説明してもらいます。  

# usage
初回はこのレポジトリを clone してください。  
``
$ git clone https://github.com/tmu-nlp/100knock2021
``

各Chapterのはじめでは、各Chapterのディレクトリへ移動し、ブランチを切って、自分用の作業用ブランチで作業してください。  
ブランチの名前は自分の名前にしてください(例：北大太郎の場合、hokudai_taro)
```
# 取り組むChapterへ移動
$ cd chapter1
#新規ブランチ作成
$ git branch hokudai_taro
#作成したブランチに切り替え
$ git checkout hokudai_taro
```

コードを書いたら自身のブランチの remote repository に push してください。 ファイル名はすべて二桁の数字にしてください（例: knock00.py）  
```
$ git add ./knockXX.py
$ git commit -m 'your message'
$ git push origin hokudai_taro
```
毎週1章分の担当者が書いたコードのレビューを行い、問題がなければ、mainへマージされます。

# 注意事項
わからないところは積極的に TA か研究室の人に聞いてください。 
他の人のディレクトリを変更することは絶対にやめてください。 （他の人のコードを閲覧したい場合は、Web サイト上から閲覧してください。）  

# メモ・相談
・ブランチ名は本名でなくてもおｋとする?  
・ファイル形式は統一する? それとも混合でおｋ?(.pyもしくは.ipynb)  
