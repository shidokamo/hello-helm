# Hello Helm
GKE で Helm を使うサンプルです。

## Helm のインストール
なければインストール
```
sudo curl -L https://git.io/get_helm.sh | bash
```

## GKE のサービスアカウントを作る
```
kubectl apply -f create-helm-service-account.yaml
```

## Tiller のインストール
```
helm init --history-max 200 --service-account helm
```

## Repo の更新
```
helm repo udpate
```
