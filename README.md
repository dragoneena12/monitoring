# monitoring
サーバー群監視用ツールテンプレート

- `monitor` メトリクスを集約するサーバー
- `exporter` 各ノードに入れてメトリクスを取得する

```
docker network create --subnet=172.24.0.0/16 docker_network
sudo docker-compose up -d
```

## memo
どうやらARMだとcAdvisorがうまく動かないようなので `budry/cadvisor-arm` あたりを利用すると良い。