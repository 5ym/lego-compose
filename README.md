# certbot

legoを利用して証明書だけを取得するためのdocker-compose、メールサーバなどで証明書だけ必要な時に

## how to use

1. lego.envに下記を参照してAPIキーなどを設定

<https://go-acme.github.io/lego/dns/>

2. lego.shの内容を適宜書き換え
3. CRONでlego.shを実行するよう設定

下記参照

<https://daco.dev/blog/doodcron>
