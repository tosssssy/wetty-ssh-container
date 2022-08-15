# wetty-ssh-container

ブラウザにターミナルを埋め込み、https で wetty と通信することを目標にした練習用リポジトリ
※追記
wetty-with-ssh の方をメインに開発していく

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
