# spacemesh-service
spacemesh-service单独服务

### 复制identity.key

将数据集里的identity.key复制到node的data/identities文件夹，重命名为xxx.key(xxx随意改)

### 编译

docker build . -f ./Dockerfile --tag spacemesh-service --no-cache

### 修改docker-compose.yml

有几个数据集添加几个service, 修改volumes路径

### 启动

`docker compose up -d`
