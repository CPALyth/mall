# go-zero开发的微服务商城系统

## 1 环境配置
### (1) 克隆环境配置代码
```bash
git clone git@github.com:nivin-studio/gonivinck.git
```
### (2) 启动全部服务
```bash
docker-compose up -d
```

## 2 克隆代码
### (1) 创建code文件夹
```bash
cd ./gonivinck
mkdir ./code && cd ./code
```

### (2) 克隆本项目代码
```bash
git clone git@github.com:nivin-studio/gonivinck.git
```

## 3 运行微服务
### (1) 进入golang窗口
```bash
docker exec -it ... bash
```

### (2) 运行user微服务
- 运行user-rpc
```bash
cd mall/service/user/rpc
go run user.go
```
- 运行user-api
```bash
cd mall/service/user/api
go run user.go
```

### (3) 运行product微服务
...