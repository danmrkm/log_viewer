# log viewer

## 事前準備
ElasticSearch の利用にプロセスが使用可能なメモリマップ領域の最大数を変更する必要がある。

### Docker for Mac
```
screen ~/Library/Containers/com.docker.docker/Data/vms/0/tty
sysctl -w vm.max_map_count=262144
```
