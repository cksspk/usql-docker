## 简述

源码地址：[https://github.com/xo/usql](https://github.com/xo/usql)

使用 GitHub Action 自动构建的 `docker-usql` 

## 使用

**拉取镜像**

```sh
docker pull cksspk/usql:latest
```


**启动容器**

```sh
docker run --rm -it \
--net=host -v $(pwd)/data:/data \
cksspk/usql:latest \
my://root@127.0.0.1:23306/
```
