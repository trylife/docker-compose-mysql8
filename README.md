# docker-compose-mysql8

docker-compose-mysql8

# 使用

### 1. 安装 docker-desktop 
   
- https://docs.docker.com/docker-for-windows/install/
- https://www.runoob.com/docker/windows-docker-install.html

### 2. 克隆本仓库

### 3. 复制 `docker-compose-ie.yml` 为 `docker-compose.yml`

### 4. 如果端口冲突可以修改 `11100:3306` `11101:8080`

- `:` 前第一个数字代表本机端口, 后边的数字代表容器端口

### 5. 命令行进入到 `docker-compose-mysql8` 目录下

```bash
# 前台运行
docker-compose up

# 后台运行
docker-compose up -d 

# 关闭
docker-compose down 
```

### 6. 使用自带的adminer链接MySQL

http://localhost:11101/

- 服务器: `mysql`
- 用户名: `root`
- 密码: `123456`

### 7. 容器外的项目连接mysql, 使用4中的端口 


