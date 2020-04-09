## 开始使用

> git clone https://github.com/goukey/Aria2-docker.git Aria2-docker

> cd Aria2-docker

> docker-compose up -d


## 关闭容器

> cd Aria2-docker

> docker-compose down

## 升级容器

> cd Aria2-docker

> docker-compose down  #停止容器

> git pull

> docker-compose pull  #更新image

> docker-compose up -d  #启动容器

> docker image prune  #删除旧的镜像
