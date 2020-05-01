# monitoring
ラズパイとかの監視をするやつ

```
docker network create --subnet=172.24.0.0/16 docker_network
sudo docker-compose up -d
```

## 追記
どうやらARMだとcAdvisorがうまく動かないようなので `budry/cadvisor-arm` あたりを利用すると良いかと思います。