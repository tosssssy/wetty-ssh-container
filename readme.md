# wetty-ssh-container

ブラウザにターミナルを埋め込み、httpsでwettyと通信することを目標にした練習用リポジトリ


![terminal](https://user-images.githubusercontent.com/65057976/184346787-1160ba32-e3a2-440c-b4c7-08f09c54c5ee.png)

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

おすすめはvscodeの拡張機能「Live Server」を使用し、起動して`http://127.0.0.1:5500`にアクセスする。その後`http://localhost:5500`に書き換える

