# dokisidpy
__このツールを利用するには、FFmpegをインストールし、必要に応じてパスを通す必要があります。__
### sidtool.py
numtoolを応用し、某ライブ配信サイトのsidから日付を計算してm3u8のURLを表示した後、連番の.tsのダウンロードとffmpegによるmp4への結合を一括でできるようにしたpythonスクリプト。<br>
何らかの要因により途中でtsの番号が飛び、ダウンロード完了を誤検知する場合があります。どうしてもうまく行かないときは手動でtsの抜けた分をダウンロードした上で、sidtoolをimportして必要部分の関数のみを利用するpythonスクリプトを組むなどしてもらえると良いと思います。アクセス過多で一時BANされている可能性もあるため、time.sleep(25行目)は念の為大きめに設定すると良いかもしれません。
### GUI_test.py
Fletで作ったsidtoolのGUIテスト版。pipでfletを入れて、 flet run GUI_test.py で動くと思います。
