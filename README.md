# container-mirrors
GFW容器桥接，通过阿里云容器镜像自动构建功能将GFW内不能拉取镜像构建到阿里云上的容器服务中

#### 项目结构说明

```shell
ingress-nginx			# 项目根目录
├─controller			# 子项目
│  └─v1.0.4			# 版本号
│ 		Dockerfile	
└─hube-webhook-certgen
    └─v1.1.1
 		Dockerfile	
```

