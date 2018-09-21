#### nginx镜像

##### 拉取

```
docker pull nginx:[tag]

```

##### 启动

```
docker run -d -p 80:80 --name chinaentropy_nginx  nginx
```

##### 通过Dockerfile构建nginx镜像

```
FROM nginx

```


### docker-compose 小案例

```
设备管理系统搭建
```