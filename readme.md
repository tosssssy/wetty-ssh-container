# wetty-ssh-container

ブラウザにターミナルを埋め込み、httpsでwettyと通信することを目標にした練習用リポジトリ

![スクリーンショット 2022-08-12 211222](https://user-images.githubusercontent.com/65057976/184351573-eb7b6fa4-14db-420b-8f46-5dc8d9109279.png)


## install
```
git clone https://github.com/tosssssy/wetty-ssh-container.git 
cd wetty-ssh-container
cd wetty-and-ssh or cd wetty-with-ssh
docker compose up --build
```

## remove
```
docker compose down
docker image rm <対象ID>
```

## iframeが接続拒否される時
originがlocalhostになっているかを確認する。

おすすめはvscodeの拡張機能「Live Server」を使用し、起動して`http://127.0.0.1:5500/index.html`にアクセスする。その後`http://localhost:5500/index.html`に書き換える

