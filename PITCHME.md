### コンテナ(Docker)についてhogehoge

勉強会用資料  
by GitPitch

---
### 目次
#### 仮想環境とコンテナの違い
#### コンテナとは
#### Docker Swarmの紹介
#### Dockerの使い方、ログ、監視

+++

仮想環境はホスト型、ハイパーバイザ型が有名

ホスト型の構成図
ハイパーバイザ型の構成図
コンテナの構成図

コンテナは隔離された空間で任意のプロセスを実行する事
コンテナは仮想環境というよりはプロセスに近い

Portainerの紹介
docker run -d -p 9000:9000 -v "/var/run/docker.sock:/var/run/docker.sock" portainer/portainer

---
#### コンテナとは

