# Hello Helm
GKE で Helm を使うサンプルです。

## Helm のインストール
なければインストール
```
sudo curl -L https://git.io/get_helm.sh | bash
```

## Tiller のインストール
```
helm init --history-max 200
```

## Repo の更新
```
helm repo udpate
```
