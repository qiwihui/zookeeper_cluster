# zookeeper cluster deployment

## standalone

```bash
docker run -d --name zkserver -v /opt/zkdata:/data -v /opt/zklog:/datalog -p 2181:2181 --restart always zookeeper
```

## cluster on one host with zkui

`docker-compose`

## cluster on many hosts

to be continued.