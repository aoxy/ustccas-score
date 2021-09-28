# 一个「又不是不能用」的给 USTC 学生查成绩的工具

> 基于 https://github.com/zzh1996/ustccas-revproxy

## 用法

### 环境

```shell
# 安装docker和docker-compose
$ sudo apt update
$ sudo apt install docker.io
$ sudo apt install docker-compose
```

### 拉仓库

```shell
$ git clone https://github.com/aoxy/ustccas-score.git
```

### 填写成绩

在[ustccas-score/auth/score.csv](ustccas-score/auth/score.csv)中

### 开启服务

```shell
# 在ustccas-score目录下
$ sudo docker-compose up
```

### 查成绩

浏览器输入 ip (连接eduroam有公网ip)地址，登录即可跳转到成绩结果页面，想再查一次就在 ip 后接上`/logout`退出再次登录（又不是不能用
