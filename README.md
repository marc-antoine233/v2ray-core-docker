# Docker image

由于 [原项目](https://hub.docker.com/r/v2fly/v2fly-core) 的镜像有差不多半年没有更新，重新构建了一个并上传至 [dockerhub](https://hub.docker.com/r/marcantoine153/v2ray-core)

## Usage

```bash
docker run --rm marcantoine153/v2fly-core help

docker run --name v2ray marcantoine153/v2fly-core $v2ray_args (help, eun etc...)

docker run -d --name v2ray -v /path/to/config.json:/etc/v2ray/config.json -p 10086:10086 marcantoine153/v2fly-core run -c /etc/v2ray/config.json 

# If you want to use v5 format config
docker run -d --name v2ray -v /path/to/config.json:/etc/v2ray/config.json -p 10086:10086 marcantoine153/v2fly-core run -c /etc/v2ray/config.json -format jsonv5
```
