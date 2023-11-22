# Docker image

由于 [原项目](https://hub.docker.com/r/v2fly/v2fly-core) 的镜像有差不多半年没有更新，重新构建了一个并上传至 [dockerhub](https://hub.docker.com/r/marcantoine153/v2ray-core)

## 拉取镜像

```bash
docker pull marcantoine153/v2ray-core:latest
```

## 启动容器

```bash
docker compose up -d
```

## (可选) 重新构建镜像

```bash
docker compose build
```
