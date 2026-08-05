SNOW MAP v0.13.28 追加音源

以下2ファイルをGitHubの sounds フォルダへ追加してください。

- dome-events-normal-v1.mp3
- dome-events-peak-v1.mp3

仕組み:
- ドームを選んだユーザー操作の瞬間に長尺トラックを開始
- トラック冒頭には移動中の無音を収録
- 到着時に波音がフェードアウト
- 到着5秒後に最初の歓声または手拍子
- 通常時間と18〜20時で、その後のイベント頻度が異なる
- 遅延したplay()を使わないためSafariのNotAllowedErrorを回避

追加後、index.htmlをv0.13.28へ丸ごと差し替えてください。
