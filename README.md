# dispost

discordのWebhookを利用してテキストまたはファイルをdiscordに送信するShellScript

isuconで解析結果とかをdiscordに貼るのがめんどくさかったので書いた

## 使用方法

スクリプトの `url=YOUR WEBHOOK URL` の部分に使用したいWebhookのURLを入れる

`./dispost -t hogehoge` で hogehoge と送信

`./dispost -f hoge.txt` で hoge.txt をアップロード

`echo hoge | ./dispost` で hoge と送信

`/usr/local/bin/dispost` とかに置いて使うと便利かも
